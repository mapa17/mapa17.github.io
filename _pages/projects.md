---
#layout: page
permalink: /projects/
title: "Stuff I was working on"
excerpt: "All kind of different personal projects"
#toc: true

author_profile: false
# Keep this in order to have top menu
#sidebar:
# nav: "special"
---

{% for project in site.projects %}
<h2>
    <a href="{{ project.url }}">
    {{ project.title }}
    </a>
</h2>
{{ project.excerpt }}
{% comment %} <p>{{ project.content | markdownify }}</p> {%endcomment%}
{% endfor %}
