---
layout: docs
title:  "карта сайта"
permalink: /site-map/
---
<div class="row">
	<div class="large-6 columns"><h4>ассоциация</h4>
		<ul>
      {% for pg in site.pages %}{% if pg.categories == 'ассоциация' %}<li><a href="/avpnw{{pg.url}}">{{pg.title}}</a></li>{% endif %}{% endfor %}
   		</ul>
   	</div>
	<div class="large-6 columns"><h4>специалистам</h4>
		<ul>
      {% for pg in site.pages %}{% if pg.categories == 'специалистам' %}<li><a href="/avpnw{{pg.url}}">{{pg.title}}</a></li>{% endif %}{% endfor %}
   		</ul>
   	</div>
   		<div class="large-6 columns"><h4>городской центр</h4>
		<ul>
      {% for pg in site.pages %}{% if pg.categories == 'горцентр' %}<li><a href="/avpnw{{pg.url}}">{{pg.title}}</a></li>{% endif %}{% endfor %}
   		</ul>
   	</div>
   		<div class="large-6 columns"><h4>контакты</h4>
		<ul>
      {% for pg in site.pages %}{% if pg.categories == 'контакты' %}<li><a href="/avpnw{{pg.url}}">{{pg.title}}</a></li>{% endif %}{% endfor %}
   		</ul>
   	</div>
</div>