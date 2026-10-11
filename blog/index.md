---
layout: default
title: "Blog"
description: "Notes on PKI, key management, secure software and post-quantum cryptography, with runnable labs."
permalink: /blog/
---

<section class="content-section" markdown="1">

## Blog

Notes from building and breaking cryptographic infrastructure: certificates, key management, secure C++ and Rust, and post-quantum migration. Each post comes with code you can run.

{% if site.posts.size > 0 %}
{% for post in site.posts %}
<div class="research-card">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></h3>
  <p class="post-date">{{ post.date | date: "%-d %B %Y" }}</p>
  {% if post.description %}<p>{{ post.description | escape }}</p>{% endif %}
</div>
{% endfor %}

Subscribe [via RSS]({{ '/feed.xml' | relative_url }}).
{% else %}
*No posts yet.*
{% endif %}

</section>
