---
layout: docs
title:  "новости"
categories: ассоциация
permalink: /assoc/news/
---
<ul>
{% for post in site.categories.news %}

      <li><span>{{ post.date | date_to_string }}</span> <h3><a href="/avpnw/{{ post.url }}">{{ post.title }}</a></h3></li>
      {{post.content}}
   
{% endfor %}
</ul>
