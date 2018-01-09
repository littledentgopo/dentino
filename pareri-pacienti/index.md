---
layout: default
title: Parerile pacientilor INODENT
description: Implanturi dentare la preturi accesibile. Tratamente inovative si abordare prietenoasa.
---

<!-- Start Hero -->

{% include hero.html %}

<!-- End Hero -->



<!-- Start Testimonials -->
<div id="testimonials" class="testimonials parallax" >
    <div class="overlay-container">
        <div class="overlay"></div>
        <div class="container-fluid">
            <div>
                {% for testimonial in site.data.testimonials %}
                    <div class="testimonial-item">
                        <svg class="icon icon-quote-left"><use xlink:href="#icon-quote-left"></use></svg>
                        <blockquote>
                            <p>{{ testimonial.description }}</p>
                            <footer>
                                <a href="{{ testimonial.link}}" class="testimonial-link"><img  rel="nofollow" src="https://graph.facebook.com/{{ testimonial.fbid }}/picture?type=normal"/> {{ testimonial.name }}</a>
                                <small>{{ testimonial.title }}</small>
                            </footer>
                        </blockquote>
                    </div>
                {% endfor %}
            </div>
            
            
            <div class="row">
                <small>Citeste mai multe review-uri pe pagina de <a href="https://www.facebook.com/dririnaalexandru/reviews" style="color:#365899">Facebook</a></small>
            </div>
        
            <div class="row">
            <div class="fb-page" data-href="https://www.facebook.com/dririnaalexandru/" data-small-header="false" data-adapt-container-width="true" data-hide-cover="true" data-show-facepile="true"><blockquote cite="https://www.facebook.com/dririnaalexandru/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/dririnaalexandru/">{{site.name}} - Dr Irina Alexandru</a></blockquote></div>
            </div>
        </div>
    </div>
</div>
<!-- End Testimonials -->