---
layout: plainpage
title: About
permalink: /archive
---
# Archive

<ul class="post-list archive-ul">
  {% for post in site.categories.page %}
    <li class="archive-li">
      <p>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </p>
    </li>
  {% endfor %}
</ul>
