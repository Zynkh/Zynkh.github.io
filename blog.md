---
layout: page
title: Blog
permalink: /blog/
---

<div class="zcontainer text-center">
  <ul class="post-list text-center">
    {% for post in site.posts %}
      <li>
        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
      </li>
      <div class="line"></div>
    {% endfor %}
  </ul>

<!--   <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p> -->
</div>