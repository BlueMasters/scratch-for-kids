---
layout: tuto
title: Je devine un nombre
order: 30
starter_kit: https://scratch.mit.edu/projects/111400103/
solution: https://scratch.mit.edu/projects/109856566/
tags:
- moyen
---

Aprés t'avoir fait deviner un nombre, c'est maintenant à moi de jouer.
Dans cet atelier, tu vas penser à un nombre et je vais essayer de le
deviner. Comme pour le jeu précédent, tu devras juste me dire si le
nombre que je propose est plus petit ou plus grand que celui auquel
tu penses.

![je-devine]({{ site.baseurl }}/media/je-devine.png)

Commence par faire une copie du [projet de base]({{page.starter_kit}}){:target="_blank"}.

Clique ensuite sur le bouton «Voir à l'intérieur»:

![voir à l'intérieur]({{ site.baseurl }}/media/inside.png)

fais une copie dans ton espace de travail en cliquant sur «remix»:

![remix]({{ site.baseurl }}/media/remix.png)

Nous avons déjà écrit les scripts des boutons pour toi. Il te reste à
écrire le script de la magicienne.

![je-devine-wizzard]({{ site.baseurl }}/media/je-devine-wizzard.png)

Comme tu peux le voir dans l'image ci-dessus, la magicienne doit réagir
à plusieurs messages. Ces messages sont envoyés par les boutons et toi, tu
dois dire ce qu'il faut faire quand un de ces messages arrive.

Par exemple, si la magicienne reçoit le message «plus grand», elle doit
proposer un nombre... plus grand.

Si tu veux, tu peux regarder le script des boutons. Voici par exemple le
bouton «plus grand»:

![je-devine-start]({{ site.baseurl }}/media/je-devine-plus-grand.png)

Quand on presse sur le drapeau vert, je dois cacher ce bouton, car la sorcière
doit d'abord expliquer comment jouer et cacher tous les boutons, sauf le bouton
«Départ»:

![je-devine-instructions]({{ site.baseurl }}/media/je-devine-instructions.png)

Quand le bouton «Départ» est pressé, on reçoit le message «départ» et on
doit alors montrer le bouton «Plus grand».

Enfin, quand le bouton «Plus grand» est pressé, on envoie le message
«plus grand» à tous les lutins.

Voilà, c'est maintenant à toi d'écrire toutes les formules magiques
(les scripts) de la magicienne.

**Bonne chance sur le parcours de la licorne.**
