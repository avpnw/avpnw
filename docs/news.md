---
layout: docs
title:  "новости"
categories: ассоциация
permalink: /assoc/news/
---
<ul>
{% for post in site.categories.news %}

      <li><span class="round alert label">{{ post.date | date_to_string }}</span> <h3>{{ post.title }}</h3></li>
      {{post.content}}
   
{% endfor %}
</ul>
