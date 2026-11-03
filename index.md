---
layout: default
title: Home
---

<div class="h-feed">
  <h2 class="p-name">Recent Posts</h2>

  <ul class="post-list">
    {% for post in site.posts %}
      <li class="h-entry">
        <h3>
          <a class="p-name u-url" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
        </h3>
        <time class="dt-published" datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%b %d, %Y" }}</time>
        <div class="p-summary">
          {{ post.excerpt }}
        </div>
      </li>
    {% endfor %}
  </ul>
</div>

## Projects
Coming soon!

## Links
<ul>
  <li><a href="{{ site.youtube_url }}" rel="me">YouTube</a></li>
  <li><a href="{{ site.business_url }}" rel="me">Business</a></li>
</ul>
