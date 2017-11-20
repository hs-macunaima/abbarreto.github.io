---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Página pessoal de Adriano B. Barreto
====================================
******

<ul>
   {% for post in site.posts limit:10 %}
       <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
   {% endfor %}
</ul>