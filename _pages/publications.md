---
title: "Quantum Optics Theory @ The University of Sydney - Publications"
layout: gridlay
excerpt: "Quantum Optics Theory @ The University of Sydney - Publications."
sitemap: false
permalink: /publications/
---


# Publications

For a full list of Sahand's publications see his [Google Scholar profile](https://scholar.google.com.au/citations?user=PVdQntQAAAAJ&hl=en&oi=ao).

## Highlights

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p><strong><a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


## Patents
<em> Philipp Schneeweiss, Jürgen Volz, Arno Rauschenbeutel, Sahand Mahmoodian, Anders Søndberg Sørensen</em><br />Device for generating individual photons <br /> <a href="https://patents.google.com/patent/WO2021052606A1/en?inventor=Sahand+MAHMOODIAN&oq=inventor:(Sahand+MAHMOODIAN)"> PCT/EP2019/075386 (2019)

<em> Sahand Mahmoodian, Immo Nathanael Sollner, Søren Stobbe, Peter Lodahl</em><br /> Efficient spin-photon interface using glide-plane-symmetric waveguide  <br /> <a href="https://patents.google.com/patent/US10261250B2/en?inventor=Sahand+MAHMOODIAN&oq=inventor:(Sahand+MAHMOODIAN)">  US15/319,182 (2015)

<em> Søren Stobbe, Sahand Mahmoodian, Peter Lodahl, Pedro David García Fernandez</em><br /> A slow-light generating optical device and a method of producing slow light with low losses <br /> <a href="https://patents.google.com/patent/WO2016169931A1/en?inventor=Sahand+MAHMOODIAN&oq=inventor:(Sahand+MAHMOODIAN)">  PCT/EP2016/058661 (2016)

<em> Sahand Mahmoodian, Immo Nathanael Sollner, Søren Stobbe, Peter Lodahl</em><br /> Optical device having efficient light-matter interface for quantum simulations <br /> <a href="https://patents.google.com/patent/US9798083B2/en?inventor=Sahand+MAHMOODIAN&oq=inventor:(Sahand+MAHMOODIAN)">  US15/325,508 (2016)
