---
layout: page
navigation_title: Members
title: Members
permalink: /contributors/
button: true
cover: 'http://www.albionnewsonline.com/wp-content/uploads/2016/04/web-4-6-Teammates-logo.jpg'
---

Here is our Brainiacs.

<h3>Present Contributors</h3>
<div class="contributors_wrapper">
{% for contributor in site.data.present_contributors %}
<div class="contributors">

<div class="pic" style="height: 130px; width: 130px">
<img src="{{ contributor.photo }}"></div><br>
<p class="name">Name: {{ contributor.name }}</p>
<p class="contribution">Position: {{ contributor.contribution }}</p>
<p class="name"><a href="{{ contributor.resume }}" target="_blank">RESUME</a></p>

</div>

{% endfor %}
</div>
<div class="contributors_wrapper">
{% for contributor in site.data.past_contributors %}
<div class="contributors">

<div class="pic" style="height: 130px; width: 130px">

<img src="{{ contributor.photo }}"></div><br>

<p class="name">Name: {{ contributor.name }}</p>
<p class="contribution">Position: {{ contributor.contribution }}</p>
<a href="http://www.google.com/" target="_blank">GOOGLE</a>
</div>
{% endfor %}
</div>
