---
layout: default
title: Oferta implant dentar premium pret 400 de euro. Bont protetic inclus, consultatie gratuita.
description: Implant dentar de calitate Bredent fabricat in Germania, pret accesibil. Fara costuri ascunse, bontul protetic, consultatia sunt incluse in pret.
noindex: true
---

<!-- Start Hero -->

{% include hero.html %}

<!-- End Hero -->


<!-- Start About -->
<div id="oabout" class="about">
    <div class="container-fluid">
        <h2 class="section-title">Oferta implant dentar premium Bredent <br/> pret 250 euro redus cu 30%</h2>
        
        <div class="row">
            <div class="col-lg-8 col-lg-offset-2 text-center">
                <img class="img-responsive" src="/img/promo/implant-dentar-bredent-400.jpg" alt="Implant dentar Bredent pret 400 euro">
            </div>
            <br/><br/>
        </div>

        <div class="row">
            <br/><br/>

            <div class="col-sm-6">
                <h3>De ce acest pret?</h3>
                <p>
                Sunt medic dentist cu experiență de peste 10 ani (dintre care 2 ani în Marea Britanie). Sunt printre primii dentisti din Bucuresti care au inceput sa promoveze tratamentul cu implanturi dentare de calitate la preturi accesibile. Am redus prețul manoperei considerabil dar in același timp am păstrat in ofertă un implant de calitate. Bredent este un implant produs in Germania, de un producator renumit la nivel internațional. Pentru a garanta siguranța tratamentului lucrăm doar cu importatori autorizați și cu implanturi originale. Succesul acestei abordări de ani de zile il probează și mărturiile de pe pagina noastră de <a href="{{site.facebook}}/reviews" target="_blank">Facebook</a>.</p>
                
                <p>Pentru a incepe tratamentul cu implanturi dentare trebuie mai intai sa va programati pentru o consultatie. Daca aveti deja o radiografie dentara mi-o puteti trimite pe email pentru a va analiza cazul in prealabil. Daca locuiti in strainatate este bine sa luati legatura din timp pentru a stabili cat mai exact planul de tratament si timpul necesar pentru indeplinirea acestuia.</p>
                
                <p>Ma puteti contacta telefonic <a href="tel:{{ site.contact.phone }}" style="color:#3dadb2"><svg class="icon icon-phone"><use xlink:href="#icon-phone"></use></svg></a><strong><a href="tel:{{site.contact.phone}}" style="color:#3dadb2">{{site.contact.phone}}</a></strong> sau pe <strong><a href="{{ site.facebook }}" target="_blank">Facebook</a></strong>.</p>

            </div>
            <div class="col-sm-6">
                 <div class="media">
                    <div class="media-left">
                        <div class="boxed-icon">
                            <svg class="icon icon-heart"><use xlink:href="#icon-heart"></use></svg>
                        </div>
                    </div>
                    <div class="media-body">
                        <p>Care este pretul total? - Oferta de implant dentar include bonturile protetice si de vindecare. Pentru un dinte singurul cost aditional este coronita care costa 150 de euro. Pentru refacerea mai multor dinti trebuie evaluat cate implanturi si cate coronite sunt necesare.</p>
                    </div>
                </div>

                <div class="media">
                    <div class="media-left">
                        <div class="boxed-icon">
                            <svg class="icon icon-medkit"><use xlink:href="#icon-medkit"></use></svg>
                        </div>
                    </div>
                    <div class="media-body">
                        <p>Cat dureaza interventia? - In mod normal plasarea implantului dentar se efectueaza intr-o singura sedinta de aproximativ o ora, iar lucrarea se realizeaza dupa 4-6 luni dupa ce implantul se osteointegreaza. Pentru edentatii totale exista si varianta de lucrare rapida Fast &amp; Fixed  cu implanturi si lucrare in 48 de ore.</p>
                    </div>
                </div>
                
                <div class="media">
                    <div class="media-left">
                        <div class="boxed-icon">
                            <svg class="icon icon-star"><use xlink:href="#icon-star"></use></svg>
                        </div>
                    </div>
                    <div class="media-body">
                        <p>Ce implanturi folosim? - Implantul dentar <a href="http://www.bredent-medical.ro/bluesky-implant-dentar.html" target="_blank">Bredent</a> este un implant dentar premium fabricat in Germania. Datorita structurii inovative a filetului acest implant are stabilitate perfecta si o rata de succes foarte mare.</p>
                    </div>
                </div>
                
                <div class="media">
                    <div class="media-left">
                        <div class="boxed-icon">
                            <svg class="icon icon-medkit"><use xlink:href="#icon-medkit"></use></svg>
                        </div>
                    </div>
                    <div class="media-body">
                        <p>Este dureroasa interventia? - Interventia se realizeaza sub anestezie locala si este nedureroasa. Operatia este chiar mai usoara decat extractia unui dinte deoarece in cazul implanturilor dentare forma acestora este predictibila.</p>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="row">
                <div class="col-lg-12 text-center">
                   <div class="fb-comments" data-href="https://www.dririnaalexandru.ro/oferte-implant-dentar/" data-numposts="15" data-colorscheme="light" data-order-by="reverse_time"></div>   
                </div>

        </div>
    </div>
</div>
<!-- End About -->

<!-- Start 3 columns -->
<div class="three-shade-col">
    <div class="col-sm-4">
        <svg class="icon icon-envelope-o"><use xlink:href="#icon-envelope-o"></use></svg>
        <h3>Contact</h3>
        <ul>
            {% if site.contact.phone %}<li><strong>Telefon:</strong> {{ site.contact.phone }}</li>{% endif %}
            {% if site.contact.emergency %}<li><strong>Emergency:</strong> {{ site.contact.emergency }}</li>{% endif %}
            {% if site.contact.email %}<li><strong>Email:</strong> {{ site.contact.email }}</li>{% endif %}
        </ul>
    </div>
    <div class="col-sm-4 nodisplay-mobile">
        <svg class="icon icon-clock-o"><use xlink:href="#icon-clock-o"></use></svg>
        <h3>Orar</h3>
        <table>
            <tbody>
                <tr>
                    <td>Luni – Vineri</td>
                    <td>{{ site.monday_friday }}</td>
                </tr>
                <tr>
                    <td>Sambata</td>
                    <td>{{ site.saturday }}</td>
                </tr>
                <tr>
                    <td>Duminica</td>
                    <td>{{ site.sunday }}</td>
                </tr>
            </tbody>
        </table>
    </div>
    <div class="col-sm-4 nodisplay-mobile">
        <svg class="icon icon-map-marker"><use xlink:href="#icon-map-marker"></use></svg>
        <h3>Adresa</h3>
            <p>
                {{ site.contact.address }}
            </p>
    </div>
</div>
<!-- End 3 columns -->
    
    
    
    
