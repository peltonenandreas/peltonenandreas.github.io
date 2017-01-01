---
layout: default
title: BLOG
permalink: /_post/
---
    

<div class="home">

  <h1 class="page-heading"><span>POSTS</span></h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <p class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</p>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

</div>

