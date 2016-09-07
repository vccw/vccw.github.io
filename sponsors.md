---
layout: no-sponsors
title: Our Sponsors
---

Violet Crown Community Works and its festivals are made possible by our
volunteers and artists, and with the generous support of our sponsors. These
businesses and individuals provided funding and services that help us run the
festivals and sponsor local arts projects.  Join us in thanking them.

If you&apos;re interested in being a sponsor, please see <a href="/docs/2016_VCF_Sponsor.pdf">our sponsorship guide</a>.

## Gold Sponsors
<!-- $500 and up -->

<div class="container">
<div class="row">
{% for sponsor in site.data.sponsors_fall2016.gold %}
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
{% for sponsor in site.data.sponsors_fall2016.silver %}
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
{% for sponsor in site.data.sponsors_fall2016.bronze %}
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
{% for sponsor in site.data.sponsors_fall2016.friends %}{% if sponsor.url %}* [{{ sponsor.name }}]({{ sponsor.url }}){% else %}* {{sponsor.name}}{% endif %}
{% endfor %}