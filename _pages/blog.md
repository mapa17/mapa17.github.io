---
permalink: /blog/
title: "Blog"
excerpt: "All kind of stuff ..."
#toc: true

# Keep this in order to have top menu
sidebar:
 nav: "special"
---

# Latest blog posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>