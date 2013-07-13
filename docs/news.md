---
layout: docs
title:  "новости"
categories: ассоциация
permalink: /assoc/news/
---
<ul>
{% for post in site.categories.news %}

      <li class="news"><div class="news-date">{{ post.date | date_to_string }}</div> <h3>{{ post.title }}</h3></li>
      {{post.content}}
   
{% endfor %}
</ul>
