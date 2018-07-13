---
layout: page
title: blog
order: 4
---

<div class="container mx-auto always-full-width-of-container">
    {% for post in site.posts %}
    {% include post-block.html %}
    {% endfor %}
</div>
