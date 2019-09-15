---
layout: posts
title: Posts
---
# Follow our latest work
<div>
{% for post in site.posts %}
<hr>
<div class="date-post">
{{post.date | date: "%b %d, %y"}}
 | 
{{post.title}} 
</div>
{{post.content}}
{% endfor %}
</div>
