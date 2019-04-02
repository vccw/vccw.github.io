---
layout: no-sponsors
title: Our Sponsors
---

Violet Crown Community Works and its festivals are made possible by our
volunteers and artists, and with the generous support of our sponsors. These
businesses and individuals provided funding and services that help us run the
festivals and sponsor local arts projects.  Join us in thanking them.

If you want to help sponsor the festival, please see our <a href="docs/VCF%202019%20sponsorship%20packet.pdf">2019 Sponsorship packet</a>.

## Title Sponsors
<!-- $1000 and up -->

<div class="container">
<div class="row">
{% for sponsor in site.data.sponsors_spring2019.title %}
<div class="col-md-3">
    {% if sponsor.url %}<a href="{{ sponsor.url }}" target="_blank">{% endif %}
    <img class="img-rounded" src="{{ sponsor.img }}" alt="" title="{{ sponsor.name }}">
    {% if sponsor.url %}</a>{% endif %}<br>{{ sponsor.title }} Sponsor
</div>
{% endfor %}
</div>
</div>

## Gold Sponsors
<!-- $500 and up -->

<div class="container">
<div class="row">
{% for sponsor in site.data.sponsors_spring2019.gold %}
<div class="col-md-3">
    {% if sponsor.url %}<a href="{{ sponsor.url }}" target="_blank">{% endif %}
    <img class="img-rounded" src="{{ sponsor.img }}" alt="" title="{{ sponsor.name }}">
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
{% for sponsor in site.data.sponsors_spring2019.silver %}
<div class="col-md-3">
    {% if sponsor.url %}<a href="{{ sponsor.url }}" target="_blank">{% endif %}
    <img class="img-rounded" src="{{ sponsor.img }}" alt="" title="{{ sponsor.name }}">
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
{% for sponsor in site.data.sponsors_spring2019.bronze %}
<div class="col-md-3">
    {% if sponsor.url %}<a href="{{ sponsor.url }}" target="_blank">{% endif %}
    <img class="img-rounded" src="{{ sponsor.img }}" alt="" title="{{ sponsor.name }}">
    {% if sponsor.url %}</a>{% endif %}
</div>
{% endfor %}
</div>
</div>
<br>

### Friends of Violet Crown Community
<!-- $50 to $99 -->
{% for sponsor in site.data.sponsors_spring2019.friends %}{% if sponsor.url %}* [{{ sponsor.name }}]({{ sponsor.url }}){% else %}* {{sponsor.name}}{% endif %}
{% endfor %}
