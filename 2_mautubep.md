---
layout: post
title: Mau tu bep
description: Bo suu tap mau tu bep hien dai
image: assets/images/pic11.jpg
nav-menu: true
---

<section class="no-padding" id="portfolio2">
    <div class="container-fluid">
        <div class="row no-gutter">
		
		{% for style in site.portfolios %}
            <div class="col-sm-6">
                <a href="#">
                    <img src="{{site.baseurl}}/assets/images/tubep/{{ style.image }}" class="img-responsive" alt="">
                    <!-- <div class="portfolio-box-caption"> -->
                        <!-- <div class="portfolio-box-caption-content"> -->
                            <!-- <div class="project-category text-faded"> -->
                                <!-- {{ style.category }} -->
                            <!-- </div> -->
                            <!-- <div class="project-name"> -->
                                <!-- {{ style.project }} -->
                            <!-- </div> -->
                        <!-- </div> -->
                    <!-- </div> -->
                </a>
            </div>   
		{% endfor %}
  
        </div>
    </div>
</section>
