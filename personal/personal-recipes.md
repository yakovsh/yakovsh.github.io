---
title: Personal / Recipes
layout: page
tags: personal
---
Here are some recipes and food-related articles I have published over the years.

<span style="text-decoration:underline;">**Published outside my website/blog:**</span>

- “[Cooking is Like Programming](https://www.noom.com/company-blog/2015/08/cooking-is-like-programming/)“ (includes a recipe for a chili); Noom Team Blog; Aug 27, 2015

<span style="text-decoration:underline;">**Recipes published here:**</span>

<ul>
{% for post in site.categories.recipes %}
      <li><a href="{{ post.url }}">
          {{ post.title | replace: "Recipe: ", "" }}
          ({{ post.date | date: "%-d %B %Y"}})
      </a></li>
{% endfor %}
</ul>