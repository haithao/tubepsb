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
	<div class="row row-no-gutters">
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
			<h2>Massa libero</h2>
		</header>
		<p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus pharetra. Pellentesque condimentum sem. In efficitur ligula tate urna. Maecenas laoreet massa vel lacinia pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus amet pharetra et feugiat tempus.</p>
		<ul class="actions">
			<li><a href="2_mautubep.html" class="button next">Get Started</a></li>
		</ul>
	</div>
</section>

</div>
