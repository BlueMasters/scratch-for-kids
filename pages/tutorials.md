---
layout: page
title: tutoriels
order: 2
---


## Tutoriels disponibles

Voici une list des tutoriels disponibles, par ordre de difficulté.
 

<ul class="tutos-list">
    {% assign tutorials = (site.pages | where: "layout" , "tutos" | sort: "order" )%}
    {% for page in tutorials %}
      <li>
        <div class="tuto-meta">{{ page.tags | join:", " }}</div>
        <div class="tuto-title">
          <a class="tuto-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a>
        </div>
      </li>
    {% endfor %}
  </ul>
