---
description: Windows 7 使用 gitbook-cli serve 和 build 时随机出现 ENOENT 的问题.
---

# Windows 7 使用 gitbook-cli serve 和 build 时随机出现 ENOENT 的问题

## 问题描述
- 平台: Windows 7
- node.js: v8.10.0
- gitbook: 3.2.3
- ```gitbook server``` 或者 ```gitbook build``` 时会出现
```
Error: ENOENT: no such file or directory, stat '...\gitbook\gitbook-plugin-x\somefile'
```

## 问题原因
未调查

## 解决办法
1. 编辑文件 ```%USERPROFILE%\.gitbook\versions\3.2.3\lib\output\website\copyPluginAssets.js```
2. 找到函数 ```copyAssets``` 和 ```copyResources```
3. 将这两个函数返回语句中的 ```confirm``` 值由 ```true``` 改为 ```false```

## 参考
1. [random errors when using gitbook plugin on running "gitbook serve". #1309](https://github.com/GitbookIO/gitbook/issues/1309)
