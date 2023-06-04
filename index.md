---
layout: default
title: Home
desc: 'Saurabh Meena's blog'
sitemap:
  priority: .8

---

# About

<div itemscope itemtype="http://data-vocabulary.org/Person">
My name is <span itemprop="name">Saurabh Meena</span>. I usually appear online as <em itemprop="nickname">mr_fountainhead</em>. I am a <span itemprop='role'>Product professional</span> with experience in Consulting, Growth, B2C & Interal Products. I intend to convert my diary into blog posts answering questions that I care about.
</div>


<br>
<div>
This website is open sourced on <a href="https://github.com/err0w/err0w.github.io">github at err0w/err0w.github.io</a>. Feel free to submit pull requests when you find my typos.
</div>


## Online Presence

- <a rel="me" href="{{ site.twitter }}" title="Saurabh Meena's Twitter ">@mr_fountainhead on Twitter</a>
- <a rel="me" href="{{ site.instagram }}" title="Saurabh's insta">@mr_fountainhead on Instagram</a>
- <a rel="me" href="{{ site.linkedin }}" title="Saurabh's linkedin">Saurabh Meena on LinkedIn</a>

## Project Graveyard
- <a rel="me" href="https://www.facebook.com/papercutnotebooks/" title="Papercut">PaperCut Notebooks</a>
- <a rel="me" href="http://bitadda-crypto.weebly.com/" title="BitAdda">Bitadda Crypto Exchange</a>
- <a rel="me" href="https://sourabhmeena381.wixsite.com/adowe" title="AdoWe">Adowe/GoTuna</a>

## Blog Posts

<ul class="features">
{% for post in site.posts  %}
    <li><a href="{{ post.url }}">{{ post.title }}</a><span class="date">{{ post.date | date: "%B %Y"  }}</span></li>
{% endfor %}
</ul>
<hr>
