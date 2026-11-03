---
layout: default
title: About
permalink: /about
---

<div class="h-card">
  <h1 class="p-name">{{ site.author.name }}</h1>
  <div class="p-note">
    {{ site.author.bio | markdownify }}
  </div>
  <a class="u-url" href="{{ site.url | absolute_url }}" hidden></a>
  <a class="u-email" href="mailto:{{ site.author.email }}" hidden></a>
</div>
