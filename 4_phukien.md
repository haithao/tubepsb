---
layout: landing
title: PHU KIEN TU BEP
description: Tu van phu kien tu bep hien dai
image: assets/images/00a-Banner.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<!-- <section class="no-padding" id="one">	 -->
    <!-- <div class="container-fluid"> -->
	<!-- <div class="row-no-gutters"> -->
		<!-- {% assign image_files = site.static_files | where: "image", true %} -->
		<!-- {% for image in image_files %}	 -->
        <!-- {% if image.path contains 'assets/images/auto-image/cariny' %} -->
		<!-- <div class="col-lg-4 col-sm-4"> -->
			<!-- <a href="#" class="portfolio-box"> -->
				<!-- <img src="{{site.baseurl}}{{ image.path }}" class="img-responsive" alt=""> -->
			<!-- </a> -->
		<!-- </div>  -->
        <!-- {% endif %} -->
		<!-- {% endfor %} -->
	<!-- </div> -->
    <!-- </div> -->
<!-- </section> -->

<section class="no-padding" id="photos">
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