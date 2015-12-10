---
title: Accueil en Include
layout: default
---

<div class="row">
	{% for post in site.posts %} 
		<div class="col-md-4 img-portfolio">
		<h3>
			<a href="{{ post.url }}">{{ post.title }}</a>
		</h3>
			<p>{{ post.content }}</p>
		</div>
	{% endfor %}
</div>

