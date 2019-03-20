---
title: Documentation
layout: default
permalink: /Documentation
---

## Documentation

My posts for poking around technology and when I wrote the steps down. Hope it helps you with your play and productivity. I am not a fan of policing comments but if I were to have a comment section it would be here.  I have three options that I would consider, Discuss, a link to a federated web mastodon account, or nothing.

{% for post in site.posts %}
     <h2> <a href="{{site.categories.documentation}}">{{post.title}}</a></h2>
     <p> {{post.date}}
       {{post.content | strip_html | truncate: 144 }} </p>

 {% endfor %}
