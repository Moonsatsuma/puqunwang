---
layout: page
show_meta: false
title: "How to survive your PhD"
subheadline: "Outreach"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/phd/"
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
