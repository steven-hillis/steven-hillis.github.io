---
layout: post
title: Welcome!
---

Neat, you found my website! You can find more on my social links. 

{% if post.content.size > post.excerpt.size %}
<p><a href="{{ post.url }}">(READ MORE)</a></p>
{% endif %}
