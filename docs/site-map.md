---
layout: docs
title:  "карта сайта"
permalink: /site-map/
---
      {% for categorie in page.categories %}
            <div class="large-6 columns">
            <h4>{categorie}</h4>
            <ul>

            </ul>
            </div>
        {% end for %}
