---
layout: page
title: writing
permalink: /writing/index.html
order: 4
---
<!--<div class="container col-9 mt-2">-->
<div class="container mx-auto">
    {% for post in site.writing %}
    {% include post-block-no-date.html %}
    {% endfor %}
</div>
