---
layout: page
permalink: /thoughts/
title: thoughts
description: 
---

Blog coming soon.

<ul class="post-list">
{% for poem in site.thoughts reversed %}
    <li>
        <h2><a class="poem-title" href="{{ poem.url | prepend: site.baseurl }}">{{ poem.title }}</a></h2>
        <p class="post-meta">{{ poem.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>