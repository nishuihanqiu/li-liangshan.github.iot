---
layout: page
title: About
description: 一起走过的日子，追梦求圆。
keywords: Liangshan Li, 李良山
comments: true
menu: 关于
permalink: /about/
---

如果可以的话，我愿一生一世陪伴你，

可是现在我只能一心一意的追求你，

每一分每一秒都会想着你^@^。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
