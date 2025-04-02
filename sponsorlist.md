---
layout: no-sponsors
title: Our Sponsors
---

Violet Crown Community Works and its festivals are made possible by our
volunteers and artists, and with the generous support of our sponsors. These
businesses and individuals provided funding and services that help us run the
festivals and sponsor local arts projects.  Join us in thanking them.

If you want to help sponsor the festival, please see our
<a href="vcf_sponsor">sponsorship application</a>.

## Title Sponsors
<!-- $1000 and up -->

<div class="container">
<div class="row">
{% for sponsor in site.data.sponsors_spring2025.title %}
<div class="col-md-3 text-center">
    {% if sponsor.url %}<a href="{{ sponsor.url }}" target="_blank">{% endif %}
    <img class="img-rounded" src="/{{ sponsor.img }}" alt="" title="{{ sponsor.name }}">
    {% if sponsor.url %}</a>{% endif %}<p>{{ sponsor.title }} Sponsor</p>
</div>
{% endfor %}
</div>
</div>

## Gold Sponsors
<!-- $500 and up -->

<div class="container">
<div class="row">
{% for sponsor in site.data.sponsors_spring2025.gold %}
<div class="col-md-3 text-center">
    {% if sponsor.url %}<a href="{{ sponsor.url }}" target="_blank">{% endif %}
    <img class="img-rounded" src="/{{ sponsor.img }}" alt="" title="{{ sponsor.name }}">
    {% if sponsor.url %}</a>{% endif %}
</div>
{% endfor %}
</div>
</div>
<br>

## Silver Sponsors
<!-- $250 to $499 -->

<div class="container">
<div class="row">
{% for sponsor in site.data.sponsors_spring2025.silver %}
<div class="col-md-3 text-center">
    {% if sponsor.url %}<a href="{{ sponsor.url }}" target="_blank">{% endif %}
    <img class="img-rounded" src="/{{ sponsor.img }}" alt="" title="{{ sponsor.name }}">
    {% if sponsor.url %}</a>{% endif %}
</div>
{% endfor %}
</div>
</div>
<br>

## Bronze Sponsors
<!-- $100 to $249 -->

<div class="container">
<div class="row">
{% for sponsor in site.data.sponsors_spring2025.bronze %}
<div class="col-md-3 text-center">
    {% if sponsor.url %}<a href="{{ sponsor.url }}" target="_blank">{% endif %}
    <img class="img-rounded" src="/{{ sponsor.img }}" alt="" title="{{ sponsor.name }}">
    {% if sponsor.url %}</a>{% endif %}
</div>
{% endfor %}
</div>
</div>
<br>

## Friends of Violet Crown Community
<!-- $50 to $99 -->
<h4><ul>{% for sponsor in site.data.sponsors_spring2025.friends %}{% if sponsor.url %}<li><a href="{{ sponsor.url }}">{{ sponsor.name }}</a></li>{% else %}<li> {{sponsor.name}}</li>{% endif %}
{% endfor %}</ul></h4>
