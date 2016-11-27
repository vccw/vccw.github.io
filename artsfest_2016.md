---
layout: default
title: Violet Crown Arts Festival (December 2016)
---

<div class="container">
	<div class="row">
		<div class="col-md-4">
			<h1>2016 Violet Crown Arts Festival</h1>
			<h2>
				<p>Saturday,<br>
				<strong>December 3rd</strong><br></p>
				<p>Sunday,<br>
				<strong>December 4th</strong></p>
				<p>10AM to 5PM</p>
				<p><a href="https://goo.gl/maps/xov1S">6700 Yates Ave,
				<br>Austin, TX 78757</a>
				<br><small>outside Brentwood Elementary School</small></p>
			</h2>
		</div>
		<div class="col-md-4"><img src="img/Accordion player 400x496.png" title="Many thanks to artist Jean Graham for the use of images from the Wall of Welcome" class="img-responsive"></div>
	</div>
	<div class="row"><p><br><br></p></div>
	<div class="row">

		<div class="col-md-8">

			<h3>The Festival</h3>

			<p>Great quality artwork is standard, unique designs, expected.
			New and experienced local talent showcase paintings, sculpture,
			pottery, and fiber art, woodworking, glass art of all kinds,
			metal work and jewelry. Shop for hand-made gifts and support
			artistic cottage businesses in a family friendly environment.</p>

			<p>Brentwood Elementary School a Creative Learning Classroom
			Initiative, is host for Violet Crown Arts Festival in the heart
			of the Brentwood &amp; Crestview neighborhoods that VCCW
			supports. Located in the west parking lot. Admission is free.</p>

		</div>

	</div>

	<div class="row"><div class="col-md-8">

		<h3>Facebook</h3>

		<p>Stay informed on <a href="https://www.facebook.com/events/102067300252996/">our Facebook event page
		for the Violet Crown Arts Festival</a> with updates on the artists, music and food trucks.</p>

	</div></div>

	<div class="row"><div class="col-md-8">

		<h3>Getting There</h3>

		<p>Festival site is the west parking lot adjacent to Brentwood Park
		and school. Parking is available in the neighborhood, but you are
		encouraged to walk, run, bike, carpool with friends and family or
		take Capitol Metro. Bus lines 3, 5, 320 &amp; 803 are within a 15 minute
		walk.</p>

	</div></div>

	<div class="row">
	<div class="col-md-5">

		<h3>Music</h3>

		<p>Saturday</p>
		<ul>
		<li>10:00 - 11:30   Feet First</li>
		<li>12:00 -  3:00   <a href="https://www.youtube.com/watch?v=68CgHD25fJ4">Teddy &amp; the Talltops</a></li>
		<li>3:00 -   5:00   <a href="http://pksax.com/">Paul Klemperer Trio</a></li>
		</ul>

		<p>Sunday</p>
		<ul>
		<li>10:00 - 11:00   <a href="http://bethanybecker.com">Bethany Becker</a></li>
		<li>11:30 -  1:00   The Bouza Boys</li>
		<li>1:30 -   3:00   Kathy &amp; The Kilowatts</li>
		<li>3:00 -   5:00   Diana Cantu Band</li>
		</ul>

	</div>
	<div class="col-md-3">
	<img src="img/tedroddyharp2.jpg" title="Teddy and the Talltops" class="img-rounded">
	</div>
	</div>

<!--
	<div class="row"><div class="col-md-8">

		<h3>Food</h3>

	</div></div>
-->

	<div class="row"><div class="col-md-8">

		<h3>Artists</h3>

	<div class="row">
	<div class="col-md-6">

        <ul>
        {% for artist in site.data.artists_fall2016 %}
 		{% assign mod = forloop.index | modulo: 2 %}
        {% if mod == 1 %}
        <li>{% if artist.url %}<a href="{{ artist.url }}" target="_blank">{% endif %}{{ artist.name }}{% if artist.url %}</a>{% endif %} - {{ artist.description }}</li>
        {% endif %}
        {% endfor %}
        </ul>

    </div>
	<div class="col-md-6">

        <ul>
        {% for artist in site.data.artists_fall2016 %}
 		{% assign mod = forloop.index | modulo: 2 %}
        {% if mod == 0 %}
        <li>{% if artist.url %}<a href="{{ artist.url }}" target="_blank">{% endif %}{{ artist.name }}{% if artist.url %}</a>{% endif %} - {{ artist.description }}</li>
        {% endif %}
        {% endfor %}
        </ul>

    </div>
	</div>

	<div class="row"><div class="col-md-8">

		<h3>Contact</h3>

		<p>If you wish to exhibit at the festival, please
		<a href="artsfest_apply.html">visit our festival guidelines and
		application page</a>.  Artist applications are now open; a few spots are still available.</p>

		<p>For questions about the festival, please mail <a href="mailto:violetcrownartsfestival@gmail.com">violetcrownartsfestival@gmail.com</a>.</p>

	</div></div>
</div>


