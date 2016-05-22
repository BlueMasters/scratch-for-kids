---
layout: page
title: tutoriels
order: 2
---


## Tutoriels disponibles

Voici une list des tutoriels disponibles, par ordre de difficulté.

<ul class="post-list">
    {% for post in site.posts %}
      <li>
        <!--span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span-->
        <div class="post-meta">{{ post.tags | join:", " }}</div>
        <div class="post-title">
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </div>
      </li>
    {% endfor %}
  </ul>
