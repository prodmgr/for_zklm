---
layout: page
title: 雕&nbsp;&nbsp;漆
permalink: /carvedlacquerware/
---
{%if site.categories.carvedlacquerware == null%}

  <h1>抱歉，本类目暂时没有宝贝</h1>

{%else%}
  {% for post in site.categories.carvedlacquerware %}
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