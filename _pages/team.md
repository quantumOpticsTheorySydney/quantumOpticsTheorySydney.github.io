---
title: "Quantum Optics Theory @ The University of Sydney - Team"
layout: gridlay
excerpt: "Quantum Optics Theory @ The University of Sydney - Team"
sitemap: false
permalink: /team/
---

# Group Members

 **We are always looking for new Postdocs, PhD students, and Honours students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**

{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} </i> 
  {{ member.bio }} <br />
  {{ member.pubs }}
  
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

# Alumni

Noe Demazure  
Alexander Johnston
Elaheh Mostaani  
Justin Yu



