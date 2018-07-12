---
layout: page
title: writing
permalink: /writing/index.html
order: 5
---

A place to put all written things that aren't specifically blog articles.

{% assign sorted_pages = site.writing | sort:"order" %}
{% for item in sorted_pages %}
 <!-- <h2>{{ item.title }}</h2>-->
  <!--<p>{{ item.description }}</p>-->
  <h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
  <p>{{ item.description }}</p>
{% endfor %}
