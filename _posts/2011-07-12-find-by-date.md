---
layout: post
title: Unix Find By Date
categories: 
- unix
- commands
---
<div >
  <h2><a href="{{ page.url }}">Find by date - Unix</a></h2>
  <p>July 12, 2011 21:30</p>
  <div><p class="intro"><span class="first-letter">F</span>ind by time is often forgotten by me. Hopefully writing it down will help me remember, because it's very helpful.  I just don't use find enough to remember it.</p>
<p>
<br>
<code>
find /wherever -name "*whatever*" -mtime -60  # NEWER THAN <br>
find /wherever -name "*whatever*" -mtime +60  # OLDER THAN
</code>
<br>
</p>
<p>Credit: <a href="http://www.cyberciti.biz/faq/howto-finding-files-by-date/">This is my usual spot.</a></p></div>
</div>