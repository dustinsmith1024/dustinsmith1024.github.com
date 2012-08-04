---
layout: post
title: jQuery Data Attributes
categories: 
- jquery
- mini
- commands
---

<div>
  <div>
	<p class="intro"><span class="first-letter">W</span>orking on some random jQuery this weekend I noticed something about data-attributes that I hadn't before.  Apparently jQuery's .data() function tries to coerce any number like value into an actual JS number object.  This means data-whatever="0000" turns into whatever=0 in the .data() object. So, it is advised to use .attr() whenever you need to get the true value of an attribute.</p>
	<p>{{ page.date | date_to_string }}</p>
	</div>
</div>