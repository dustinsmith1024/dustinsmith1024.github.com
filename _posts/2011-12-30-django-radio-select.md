---
layout: post
title: Django RadioSelect Patching
categories: 
- web
- django
---
<div >
  <h2><a href="{{ page.url }}">Django RadioSelect Patching</a></h2>
  <p>December 30, 2011 06:09</p>
  <div><p class="intro"><span class="first-letter">I</span> had to change up the standard Django RadioSelect form widget today because I didn't want the label tags wrapping the input like it usually does.  This is normally okay (and semantically fine), but the label wrap can be difficult to style when using it in a list.  It was a bit confusing at first but generally simple once I figured it all out.</p>
<p>A couple good links that helped were here: 
</p><ul>
<li>
<a href="
http://stackoverflow.com/questions/5558509/django-rendering-radio-button-options-with-extra-information-from-model">Stack Overflow - Rendering Radio with Options</a>
</li>
<li>
<a href="https://code.djangoproject.com/attachment/ticket/4228/radioselect_renderer.patch">Django Patch with example</a>
</li>
</ul>
<p></p>
<p>Here's a <a href="https://gist.github.com/1538180">gist</a> with what I did:</p>
<script src="https://gist.github.com/1538180.js?file=gistfile1.py"></script><link rel="stylesheet" href="https://gist.github.com/stylesheets/gist/embed.css"><div id="gist-1538180" class="gist">
          <div class="gist-meta">
            <a href="https://gist.github.com/raw/1538180/9824e139a4a37d6aa2bfc44fe1174b298da72130/gistfile1.py" style="float:right;">view raw</a>
            <a href="https://gist.github.com/1538180#file_gistfile1.py" style="float:right;margin-right:10px;color:#666">gistfile1.py</a>
            <a href="https://gist.github.com/1538180">This Gist</a> brought to you by <a href="http://github.com">GitHub</a>.
          </div>
        </div>
</div>

<p>
I am just getting the hang of Django widgets, so if there is a better way of doing this then let me know! <a href="http://twitter.com/dsmith1024" rel="external">@dsmith1024</a>.
</p>
</div>