---
layout: page
title: writing
permalink: /writing/index.html
order: 4
---
<div class="container mx-auto px-2 py-4">
    {% for post in site.posts %}
    {% include post-block.html %}
    {% endfor %}
</div>
