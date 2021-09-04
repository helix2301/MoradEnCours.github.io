---
layout: page
title: Notebook
description: Notes
permalink: /notebook/
---

<div class="divider">
    <div class="left">
        <img id="profilepic" width="280" height="280" src="/assets/notebook.gif" alt="Profile">
    </div>
    <div class="right">
        <p>
          <span class="firstcharacter">D</span>ear Diary, I have yet to decide on the exact details of what sort of articles I will display here. Thus, I leave this section with little words as I currently have no articles published. This will hopefully change soon. Until this change transpires, we wait.
        </p>
        <p>
          And we wait.
        </p>
        <p>
          <strong> But eventually I will update this.<br/><center>For real.</center> </strong>
        </p>
    </div>
</div>
<ul>
  {% for post in site.categories.notebook %}
    <li>
        <span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
