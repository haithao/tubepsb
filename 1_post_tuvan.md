---
layout: post
title: Tu van tu bep
description: Goc chuyen gia tu van
image: assets/images/pic07.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- All post -->
<section id="one">
	<div class="inner">
	{% for post in site.posts %}
	{% if post.title != 404 | == tuvan %}
		<header class="major">
		<h1>{{ post.title }}</h1>
		</header>
		{% if post.image %}<span class="image main"><img src="{{ site.baseurl }}/{{ post.image }}" alt="" /></span>{% endif %}
		{% if post.date %}<p>{{ post.date }}</p>{% endif %}
		<p>{{ post.description }}</p>
	{% endif %}
	{% endfor %}
	</div>
</section>

</div>
