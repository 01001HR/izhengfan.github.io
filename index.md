---
layout: default
title: Fan's Farm
---

<article>
<blockquote><p> 
A researcher on robotics and computer vision. Interested in programming and typography. A fan of Golden State Warriors and Stephen Curry.
</p></blockquote>
</article>

<p style="margin-top:1.2em;margin-bottom:0;"><b>Blogs</b> | Browse by <a href="/archive#tags">Tags</a></p>
<hr>
<table>
{% for post in site.categories.en %}
<tr id="blog-table">
<td>{{ post.date | date: "%Y-%m-%d" }}</td>
<td><a class="post-list-item" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></td>
</tr>
{% endfor %}
</table>
<hr>
<p>All posts <a href="/archive">archived</a></p>
