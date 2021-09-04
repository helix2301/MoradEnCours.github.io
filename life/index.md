---
layout: page
title: Life
description: Thought
permalink: /life/
---

I will expand upon this section within the upcoming future hopefully.
<center>
Till then, here is a gif of a running penguin.

<!-- ![hippo](https://media3.giphy.com/media/aUovxH8Vf9qDu/giphy.gif) -->
<img id="life" width="280" height="280" src="/assets/life-gif.png" alt="Profile"></center>
<ul>
  {% for post in site.categories.life %}
  {% if post.type == "post" %}
    <li>
        <span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
        <meta name="description" content="{{ post.summary | escape }}">
        <meta name="keywords" content="{{ post.tags | join: ', ' | escape }}"/>
    </li>
  {% endif %}
  {% endfor %}
</ul>
