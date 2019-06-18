---
title: Da thi cong thuc te
layout: landing
description: 'Cac cong trinh da thi cong thuc te'
image: assets/images/pic07.jpg
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
        
		<div class="col-lg-4 col-sm-4">
			<a href="#" class="portfolio-box">
				<img src="{{site.baseurl}}{{ image.path }}" class="img-responsive" alt="">
			</a>
		</div> 
        
		{% endfor %}
	</div>
    </div>
</section>

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>@Donald Trump</h2>
		</header>
		<p>Không có đam mê, bạn không có năng lượng; không có năng lượng, bạn không có cái gì. Không có gì tuyệt vời trên thế giới được làm xong mà không có đam mê trong đó..</p>
		<ul class="actions">
			<li><a href="2_mautubep.html" class="button next">Get Started</a></li>
		</ul>
	</div>
</section>

</div>
