---
layout: docs
title:  "новости"
categories: ассоциация
permalink: /assoc/news/
---

{% for post in site.categories.news %}

      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="/avpnw/{{ post.url }}">{{ post.title }}</a></li>
      {{post.content}}
   
{% endfor %}
