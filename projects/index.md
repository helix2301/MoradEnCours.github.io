---
layout: page
title: Projects
description: Projects
permalink: /projects/
---
> *Without knowledge action is useless and knowledge without action is futile*

I agree with this mindset. Unapplied knowledge is nothing but wasted time. 

As someone who has spent a lot of time absorbing himself in school or university-related assignments or studying for exams, unfortunately I haven't given myself justice when it comes to envisioning my own projects. "The degree is everything," I would often here.

Yet, now I here that: "Projects and work experience are what matter most."

So I am a bit hurt by this: I wonder if my time spent before wasn't worth it. The thing is, I am, as are many, looking for a way to support myself and grow, as well as to look after my family (especially my parents as they grow older). 

So I try my best to open up opportunities for myself by learning and exploring because I want to succeed so that I can make a living, as this makes it easier for me to support others with all the skills that I have to offer. So:

* I want to contribute something that is meaningful and helpful. 

* And I need someone to give me the opportunity to work with their organisation to work on making the world better.

But I feel apprehensive whenever I read a job description from a company that tries to talk about wanting only <strong>the best of the best</strong>.

I will be honest: I have met some really smart people that I think are doing incredible things. Do I consider myself to be the greatest leetcode problem-solver, mathematician or answerer to casual interview questions, though? Not in the slightest: I am still learning.

While I know that some companies will refuse me a chance for not meeting their perfect criteria, I am not fussed. Oftentimes with these companies they speak fancy about making the world better but, really - it's whatever makes the most money for them; people are just assets and ethics is a game of "if it's not illegal by law and it's profitable, then who cares if it's actually harmful to the clients".

Myself, I care about what I create and how it affects my users. I want to make things which benefit others so my motivation is, ultimately:

> To work somewhere where this mindset is genuinely shared by my entire team.

So, as I build projects and try to improve my skillset to be more valuable and employable to help others, my mindset is this:

> <center><em>I have the absolute confidence not to be number two, but then I have enough sense to realize that there can be no number one.</em></center>

A mouthful of words on this page. But, essentially, this is the page where I document about my past, present and future projects, some of which already can be found on my [Github](https://github.com/MoradEnCours?tab=repositories).
<center>
Time to get to work!
<img width="280" height="200" src="/assets/projects.jpg"  loop alt="Profile" style="border-radius: 10%">
</center>


<ul>
  {% for post in site.categories.projects %}
    <li>
        <span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
        <meta name="description" content="{{ post.summary | escape }}">
        <meta name="keywords" content="{{ post.tags | join: ', ' | escape }}"/>
    </li>
  {% endfor %}
</ul>