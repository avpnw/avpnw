---
layout: docs
title:  "карта сайта"
permalink: /site-map/
---
      {% for categorie in page.categories %}
            <div class="large-6 columns">
            <h4></h4>
            <ul>
            {% for pag in site.pages %}
              {% if pag.categories == categorie  %}
              <li>
                <a href="/avpnw{{pag.url}}">{{pag.title}}</a>
              </li>
              {% endif %}
            {% endfor %}  
            </ul>
            </div>
        {% end for %}
