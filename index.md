---
layout: home-mautubep
title: Home
landing-title: 'Trang web giới thiệu TỦ BẾP SB'
description: giá chỉ từ 2,9tr/m ...
image: null
author: null
show_tile: false
---

<!-- three -->
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

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>@Donald Trump</h2>
		</header>
		<p>Không có đam mê, bạn không có năng lượng; không có năng lượng, bạn không có cái gì. Không có gì tuyệt vời trên thế giới được làm xong mà không có đam mê trong đó.</p>
		<ul class="actions">
			<li><a href="{{site.baseurl}}6-bao-gia-tu-bep" class="button next">Báo giá</a></li>
		</ul>
	</div>
</section>
