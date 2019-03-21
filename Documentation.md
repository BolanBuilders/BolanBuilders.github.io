---
title: Documentation
layout: default
permalink: /Documentation
---

## Documentation

My posts for poking around technology and when I wrote the steps down. Hope it helps you with your play and productivity. I am not a fan of policing comments but if I were to have a comment section it would be here.  I have three options that I would consider, Discuss, a link to a federated web mastodon account, or nothing.

<ul>
{% for category in site.categories %}
  <li><a name="{{ category | documentation }}">{{ category | documentation }}</a>
    <ul>
    {% for post in category.last %}
      <li><a href="{{ post.url }}">{{ post.content | strip_html | truncate: 144  }}</a></li>
    {% endfor %}
    </ul>
  </li>
{% endfor %}
</ul>
