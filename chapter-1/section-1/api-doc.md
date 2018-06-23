# Api Doc

### API method

{% api-method method="get" host="https://api.douban.com/v2/movie/subject/:id" path="" %}
{% api-method-summary %}
give me a movie
{% endapi-method-summary %}

{% api-method-description %}
a method that gives movie
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="id" type="string" required=true %}
movie id
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```javascript
{ "rating": { "max": 10, "average": 7.4, "stars": "40", "min": 0 }, "reviews_count": 301, "wish_count": 15937, "douban_site": "", "year": "2009", "images": { "small": "http://img3.doubanio.com/view/photo/s_ratio_poster/public/p494268647.webp", "large": "http://img3.doubanio.com/view/photo/s_ratio_poster/public/p494268647.webp", "medium": "http://img3.doubanio.com/view/photo/s_ratio_poster/public/p494268647.webp" }, "alt": "https://movie.douban.com/subject/1764796/", "id": "1764796", "mobile_url": "https://movie.douban.com/subject/1764796/mobile", "title": "机器人9号", "do_count": null, "share_url": "http://m.douban.com/movie/subject/1764796", "seasons_count": null, "schedule_url": "", "episodes_count": null, "countries": [ "美国" ], "genres": [ "动画", "冒险", "奇幻" ], "collect_count": 75018, "casts": [ { "alt": "https://movie.douban.com/celebrity/1054395/", "avatars": { "small": "http://img3.doubanio.com/view/celebrity/s_ratio_celebrity/public/p51597.webp", "large": "http://img3.doubanio.com/view/celebrity/s_ratio_celebrity/public/p51597.webp", "medium": "http://img3.doubanio.com/view/celebrity/s_ratio_celebrity/public/p51597.webp" }, "name": "伊莱贾·伍德", "id": "1054395" }, { "alt": "https://movie.douban.com/celebrity/1016673/", "avatars": { "small": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p33305.webp", "large": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p33305.webp", "medium": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p33305.webp" }, "name": "詹妮弗·康纳利", "id": "1016673" }, { "alt": "https://movie.douban.com/celebrity/1017907/", "avatars": { "small": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p55994.webp", "large": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p55994.webp", "medium": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p55994.webp" }, "name": "约翰·C·赖利", "id": "1017907" }, { "alt": "https://movie.douban.com/celebrity/1036321/", "avatars": { "small": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p42033.webp", "large": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p42033.webp", "medium": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p42033.webp" }, "name": "克里斯托弗·普卢默", "id": "1036321" } ], "current_season": null, "original_title": "9", "summary": "机器人9号（伊利亚•伍德 Elijah Wood 饰）突然醒来，发现身边的世界充满危机，四处残败，一片末世景象。9号带着一个画有三个奇怪符号的圆形物体逃到街上，幸遇发明家机器人2号（马丁•兰道 Martin Landau 饰）给自己装上了声音，但2号却不幸被机器怪兽抓走。9号找到了老兵1号（克里斯托弗•普卢默 Christopher Plummer 饰）、机械工5号（约翰•雷利 John C. Reilly 饰）、疯癫画家6号（克里斯品•格拉夫 Crispin Glover 饰）和大力士8号（弗雷德•塔塔绍尔 Fred Tatasciore 饰）。9号与5号擅自出行援救2号，危急时被女武士7号（詹妮佛•康纳利 Jennifer Connelly 饰）救下，但无意中9号却令终极机器兽复活。带着自己从哪里来以及生存使命的问题，9号决定想尽办法制服机器兽，拯救全世界……©豆瓣", "subtype": "movie", "directors": [ { "alt": "https://movie.douban.com/celebrity/1276787/", "avatars": { "small": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p1351678808.44.webp", "large": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p1351678808.44.webp", "medium": "http://img7.doubanio.com/view/celebrity/s_ratio_celebrity/public/p1351678808.44.webp" }, "name": "申·阿克", "id": "1276787" } ], "comments_count": 9203, "ratings_count": 60365, "aka": [ "9：末世决战", "九", "Number 9", "机器人9号" ] }
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



