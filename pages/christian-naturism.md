---
layout: page-fullwidth
show_meta: false
title: "Articles about Christian Naturism"
subheadline: "Knealing at the Cross, unashamed in the glory in which God created me"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/christian-naturism/"
---
<ul>
    {% for post in site.categories.christian-naturism %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>