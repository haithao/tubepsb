---
layout: landing
title: PHỤ KIỆN TỦ BẾP
description: Tư vấn phụ kiện tủ bếp hiện đại.
image: assets/images/00a-Banner.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<style>
.container-fluid {
    padding-right: 1px;
    padding-left: 1px;
    margin-right: auto;
    margin-left: auto;
}
</style>

<section id="photos">
<div class="container-fluid">
<div class="row-no-gutters">
	{% assign image_files = site.static_files | where: "image", true %}
	{% for image in image_files %}
	<div class="img_wrap">
		{% if image.path contains 'assets/images/auto-image/cariny' %}
		<a href="" class="portfolio-box">
		  <img src="{{site.baseurl}}{{ image.path }}" class="image" >	
		</a>
		{% endif %}
	</div>
   {% endfor %}
</div>
</div>
</div>

<!-- <script src="{{site.baseurl}}/js/photo-grid.js"></script> -->
<script>
function getRandomSize(min, max) {
  return Math.round(Math.random() * (max - min) + min);
}
</script>

</div>