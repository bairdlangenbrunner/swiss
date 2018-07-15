---
layout: page
title: writing
permalink: /writing/index.html
order: 4
---

<div class="container mx-auto">
<ul>
    {% for post in site.writing %}
    <li class="li-post-block" type="square">{% include post-block-no-date.html %}</li>
    {% endfor %}
</ul>
</div>
