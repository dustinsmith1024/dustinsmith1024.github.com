---
layout: post
published: false
categories: 
- responsive design
- bootstrap
- css
- less
- mini
---

<p class="intro"><span class="first-letter">I</span> am working on a style guide at work and needed to utilize Twitter Bootstrap.  We prefer to mixin Bootstrap's classes and create our own semantic naming conventions.  Easy enough, just mixin .container-fluid and .row-fluid right?  Not so much...
</p>

The mixin library doesn't expose a way to mixin those classes easily.

Might be able to do it this way: http://stackoverflow.com/questions/14695502/how-to-make-a-responsive-row-fluid-mixin-for-bootstrap

But I have made a little mixin that seems to work for me.

<script src="https://gist.github.com/dustinsmith1024/4742312.js"></script>

{{ page.date | date_to_string }}