---
layout: default
title: snnlpnet
---

<div id="home">
   <h2>Blog posts</h2>
   <ul class="posts">
      {% for post in site.posts %}
      <li><span>&gt; {{ post.date | date_to_string }}</span> <a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
   </ul>
   <p><a href="/categories.html">Categories</a>&nbsp;&nbsp;<a href="/tags.html">Tags</a> &nbsp;&nbsp;
<a href="/atom.xml"> Atom Feed.</a>&nbsp;&nbsp;<a href="/about"> About </a> </p>
</div>