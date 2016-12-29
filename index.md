---
layout: default
---

<div class="header-bar">
  <h1>Jimmy Wu</h1>
</div>

<br/>

<img class="col one right" src="/img/prof_pic.jpg">

I'm a recent grad of [Olin College](https://www.olin.edu), where I studied electrical engineering, software design, and user-centered research methodologies. Most recently I was a backend software engineer at [HubSpot](https://www.hubspot.com/products/sales), making salespeoples' lives easier with creations like an out-of-office email detector and follow-up recommendations.

Previously, I [designed and prototyped](/portfolio/1_project/index.html) early versions of the [Brightbox](https://www.generosity.com/education-fundraising/hands-on-learning-in-stem-the-brightbox--2). This involved running usability tests with children, laying out the optics, and creating a solar charging circuit.

I also [consulted](http://www.olin.edu/collaborate/scope/projects/2014_15/Ivani/) for [Ivani LLC](http://www.ivani.com) with a team of 5. In a year, we conceptualized and prototyped a [Smart Tagging system](/portfolio/2_project/index.html) for electricians and building owners - now pending IP review!

<hr/>
<br/>
<span class="contacticon center">
  <a href="https://www.github.com/jwjimmy" target="_blank"><i class="fa fa-github-square"></i></a>
  <a href="https://www.linkedin.com" target="_blank"><i class="fa fa-linkedin-square"></i></a>
</span>

<div class="col three caption">
</div>


<ul class="post-list">
    {% for post in paginator.posts %}
      <li>
        <h2><a class="post-title" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
        <p class="post-meta">{{ post.date | date: '%B %-d, %Y — %H:%M' }}</p>
        <p>{{ post.description }}</p>
        <br/>
        <hr/>
      </li>
    {% endfor %}
</ul>