---
layout: page
title: Blog
permalink: /myblog/
---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
		<h2 style="line-height:14px">
			<a href="{{ post.url }}">{{ post.title }}</a>
			<span style="font-size:12px;font-style:italic;line-height:20px" class="post-meta">Posted in {{ post.date | date_to_string }}</span>
		</h2>
	  
    </li>
  {% endfor %}
</ul>