---
title: CÔNG TRÌNH ĐÃ THI CÔNG
layout: landing
description: 'Cac cong trinh da thi cong thuc te'
image: assets/images/00b-Banner.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section class="no-padding" id="one">	
    <div class="container-fluid">
	<div class="row-no-gutters">
		{% assign image_files = site.static_files | where: "image", true %}
		{% for image in image_files %}	
        {% if image.path contains 'assets/images/auto-image/dathicong' %}
		<div class="col-lg-4 col-sm-4">
			<a href="#" class="portfolio-box">
				<img src="{{site.baseurl}}{{ image.path }}" class="img-responsive" alt="">
			</a>
		</div> 
        {% endif %}
		{% endfor %}
	</div>
    </div>
</section>

</div>
