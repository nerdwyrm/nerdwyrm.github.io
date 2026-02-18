---
layout: default
title: The Nerdwyrm Nature Journal
---

<h1>{{ site.title }}</h1>
<p><em>{{ site.description }}</em></p>

<h2>Latest Journal Entries</h2>
<ul class="posts">
{%- for post in site.posts limit: 15 -%}
  <li>
    <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
    &mdash; <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{%- endfor -%}
</ul>

<p><a href="/about/">About</a></p>
