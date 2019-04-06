---
#layout: page
permalink: /projects/
title: "A place for my projects"
excerpt: "All kind of different personal projects"
#toc: true

author_profile: false
# Keep this in order to have top menu
#sidebar:
# nav: "special"
---

# Projects

{% for project in site.projects %}
<h2>
    Project:
    <a href="{{ project.url }}">
    {{ project.title }}
    </a>
    {{ project.excerpt }}
</h2>
{% comment %} <p>{{ project.content | markdownify }}</p> {%endcomment%}
{% endfor %}


Some code 

``` python
def function(foo, var):
    print('You can do it!')
var = 13
#asi tambien
def blaaa(oki):
    pass
```