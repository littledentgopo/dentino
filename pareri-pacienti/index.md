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
                    <div class="container-testimonial">
                        <a href="{{ testimonial.link}}" class="testimonial-link" target="_blank"><img  rel="nofollow" src="https://graph.facebook.com/{{ testimonial.fbid }}/picture?type=normal"/> {{ testimonial.name }}</a>
                        <p>{{ testimonial.date }}</p>
                        <p>{{ testimonial.description }} <a href="{{ testimonial.link}}">&hellip;</a> </p>
                    </div>
                {% endfor %}
            </div>
            

            
            <div class="row">
                <small>Citeste mai multe review-uri pe pagina de <a href="{{site.contact.fb_reviews}}" style="color:#365899">Facebook</a></small>
            </div>
        
            <div class="row">
            <div class="fb-page" data-href="https://www.facebook.com/inodent.ro/" data-small-header="false" data-adapt-container-width="true" data-hide-cover="true" data-show-facepile="true"><blockquote cite="https://www.facebook.com/inodent.ro/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/inodent.ro/">{{site.name}} - Dr Irina Alexandru</a></blockquote></div>
            </div>
        </div>
    </div>
</div>
<!-- End Testimonials -->

<div>
   <div class="container-fluid">

                <div class="row">
                 <div class="col-lg-8 col-lg-offset-2 text-center">
                    <img class="img-responsive" src="/img/gallery/large/greviews1.png" alt="Implant dentar Alpha Bio pret 250 euro">
                </div>
            </div>
    </div>
</div>
