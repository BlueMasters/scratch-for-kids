---
layout: page
title: Solutions
order: 3
---

<p class="message">
  <strong>Attention</strong>! Si tu n'as pas encore fait les exercices, nous te conseillons de quitter cette page au plus vite.
  Tu te laisses ainsi les chances de faire les choses différemment... et mieux !
</p>

Tu trouveras la __solution__ des exercices en cliquant sur les liens suivants:

<ul class="tutos-list">
    {% assign tutorials = (site.pages | where: "layout" , "tuto" | sort: "order" )%}
    {% for page in tutorials %}
      <li>
        <div class="tuto-meta">{{ page.tags | join:", " }}</div>
        <div class="tuto-title">
          <a class="tuto-link" href="{{ page.solution }}" target="_blank">{{ page.title }}</a>
        </div>
      </li>
    {% endfor %}
  </ul>
Nous mettons aussi à disposition __quelques exemples de jeux et programmes__ simples à faire, et très sympa. N'hésite pas à y jeter un oeil:

<ul class="tutos-list">
      <li>
        <div class="tuto-title">
          <a class="tuto-link" href="https://scratch.mit.edu/projects/110392842/" target="_blank">poulpofolie</a>
        </div>
      </li>
  </ul>
