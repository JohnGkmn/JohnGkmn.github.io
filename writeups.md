---
layout: page
title: Writeups
subtitle: Çözüme giden yollar
permalink: /writeups/
---

ilk page denemesi..
[Gökmen DEMİR](JohnGkmn.github.io)

Devamı gelecek...

_____

<ul class="list-posts">
    {% for post in site.posts %}
        <li class="post-teaser">
            <a href="{{ post.url | prepend: site.baseurl }}">
                <span class="post-teaser__title">{{ post.title }}</span>
                <span class="post-teaser__date">{{ post.date | date: "%d %B %Y" }}</span>
            </a>
        </li>
    {% endfor %}
</ul> 

Devamı gelecek...
