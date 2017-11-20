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
{% for post in site.posts %}	
	<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
	<p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://erjjones.github.com{{ post.url }}#disqus_thread"></a></small></p>			
 {% endfor %}	
