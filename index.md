---
layout: default
title: Home
desc: 'Saurabh Meena's blog'
sitemap:
  priority: .8

---

# About

<div itemscope itemtype="http://data-vocabulary.org/Person">
My name is <span itemprop="name">Saurabh Meena</span>. I usually appear online as <em itemprop="nickname">mr_fountainhead</em>. I am a <span itemprop='role'>Product professional</span>. I intend to convert my diary into blog posts asking.
</div>

<br>
<div>
This website is open sourced on <a href="https://github.com/err0w/err0w.github.io">github at err0w/err0w.github.io</a>. Feel free to submit pull requests when you find my typos.
</div>


## Online Presence

- <a rel="me" href="{{ site.twitter }}" title="Saurabh Meena's Twitter ">@mr_fountainhead on Twitter</a>
- <a rel="me" href="{{ site.instagram }}" title="Saurabh's insta">@mr_fountainhead on Instagram</a>
- <a rel="me" href="{{ site.linkedin }}" title="Joe's linkedin">Saurabh Meena on LinkedIn</a>

## Blog Posts

<ul class="features">
{% for post in site.posts  %}
    <li><a href="{{ post.url }}">{{ post.title }}</a><span class="date">{{ post.date | date: "%B %Y"  }}</span></li>
{% endfor %}
</ul>
<hr>
