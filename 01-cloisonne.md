---
layout: page
title: 景&nbsp;泰&nbsp;蓝
permalink: /cloisonne/
---

{%if site.categories.cloisonne == null%}

  <h1>no product found</h1>

{%else%}

  {% for post in site.categories.cloisonne %}
  <div class="cangyun-layout-cell layout-item-4" style="float:left">
    <!-- {{ post.excerpt }} -->
    <a href="{{post.url}}">
      <div class="cangyun-page-img-thumb">
        <img src="{{post.mainpicurl}}" style="width:100%" />
      </div>
      <h2 style="text-align:center;">
      {{post.title}}
      </h2>
    </a>
  </div>
  {% endfor %}
{%endif%}