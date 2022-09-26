---
layout: default
title: A More Voluminous Selection of the Works
permalink: /voluminous-selection-of-works/
---

{%- if site.posts.size > 0 -%}
{%- for post in site.posts -%}
## [{{ post.title | escape }}]({{ post.url | relative_url }}) ({{ post.date | date: "%Y" }})
{{ post.excerpt | strip_newlines }}
<br/>
{%- endfor -%}
{%- endif -%}
