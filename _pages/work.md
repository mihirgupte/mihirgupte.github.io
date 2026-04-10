---
layout: single
title: "Work"
permalink: /work/
author_profile: true
toc: true
toc_label: "Contents"
---

## Research Papers

Below is a collection of my research papers and work:

{% assign papers = site.papers | sort: 'date' | reverse %}
{% if papers.size > 0 %}
  {% for paper in papers %}
### [{{ paper.title }}]({{ paper.url }})
**Date:** {{ paper.date | date: "%B %Y" }}  
{{ paper.excerpt }}

[Read More →]({{ paper.url }})

---

  {% endfor %}
{% else %}
No papers yet. Check back soon!
{% endif %}

## Blog Posts

{% assign posts = site.posts | sort: 'date' | reverse %}
{% if posts.size > 0 %}
  {% for post in posts %}
### [{{ post.title }}]({{ post.url }})
**Date:** {{ post.date | date: "%B %Y" }}  
{{ post.excerpt }}

[Read More →]({{ post.url }})

---

  {% endfor %}
{% else %}
No blog posts yet. Check back soon!
{% endif %}
