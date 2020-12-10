---
layout: page
title: Hello there! 😊
subtitle: My name is André
sitemap:
  priority: 0.9
---
<picture>
  <source srcset="{{ '/assets/img/bws.webp' | prepend: site.baseurl }}" id="about-img" type="image/webp">
  <source srcset="{{ '/assets/img/bws.png' | prepend: site.baseurl }}" id="about-img" type="image/png"> 
  <img src="{{ '/assets/img/bws.png' | prepend: site.baseurl }}" id="about-img">
</picture>

<div id="describe-text">
	<p>I love to help teams build awesome web applications.</p>
	<p>Enthusiast about distributed systems, UX, books, running and <strike>cooking</strike> eating.</p>
	<p><strong>Think, then execute!</strong></p>
</div>