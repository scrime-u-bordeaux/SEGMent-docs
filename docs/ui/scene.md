---
layout: default
title: Scene
parent : L'interface utilisateur
nav_order: 4
has_children: false
has_toc: false

permalink: /ui/canvas.html

description: "Pour découvrir l'interface de SEGMent"

---

# Canvas

Le canvas est l'élément central de l'éditeur SEGMent: c'est la partie
ou les scènes du jeu sont disposées et reliées entre elles.

Plusieurs interactions sont possibles dans le canvas.

## Ajouter de nouvelles scènes

Cela se fait via glisser-déposer depuis l'inspecteur.

![Alt text](https://scrime-u-bordeaux.github.io/SEGMent-docs/assets/images/ui/scene/scene-drop.png "Scene drop")

## Se déplacer dans le canvas

Deux possibilités : en déplaçant le fond avec la souris, ou bien avec
les barres de défilement à droite et en bas du canvas.

![Alt text](https://scrime-u-bordeaux.github.io/SEGMent-docs/assets/images/ui/scene/scene-drag.png "Scene drag")

## Changer le niveau de zoom

Cela se fait en utilisant Ctrl + la molette de la souris,
ou bien Cmd (touche pomme) + mouvement du trackpad selon le matériel utilisé.

## Déplacer des éléments du canvas

Pour les scènes, cela se fait en déplaçant leur barre de titre.

![Alt text](https://scrime-u-bordeaux.github.io/SEGMent-docs/assets/images/ui/scene/scene-drag-scence.png "Scene drag")

Pour tous les autres objets, ils peuvent être déplacés simplement en les bougeant
avec la souris :

![Alt text](https://scrime-u-bordeaux.github.io/SEGMent-docs/assets/images/ui/scene/object-drag.png "Object drag")

## Créer des objets

Cela se fait via glisser-déposer depuis l'inspecteur vers une scène.

![Alt text](https://scrime-u-bordeaux.github.io/SEGMent-docs/assets/images/ui/scene/create-object.png "Scene drag")

## Copier des scènes et des objets

Cela se fait via les raccourcis standards : Ctrl-C / Ctrl-V ou Cmd-C / Cmd-V sur Mac.

![Alt text](https://scrime-u-bordeaux.github.io/SEGMent-docs/assets/images/ui/scene/copy.png "Scene copy")


## Redimensionner des scènes et des objets

Cela se fait en glissant-déplaçant la poignée grise située en bas à droite
des objets: scènes, images, etc.

![Alt text](https://scrime-u-bordeaux.github.io/SEGMent-docs/assets/images/ui/scene/object-resize.png "Object drag")

## Créer des transitions

Cela se fait en sélectionnant une ancre autour d'un objet, puis en
effectuant un glisser-déposer vers une ancre d'une autre scène.

![Alt text](https://scrime-u-bordeaux.github.io/SEGMent-docs/assets/images/ui/scene/create-scene-transition.png "Scene drag")

Il est possible de créer des transitions depuis certains objets vers des
scènes.

![Alt text](https://scrime-u-bordeaux.github.io/SEGMent-docs/assets/images/ui/scene/create-object-transition.png "Object drag")

Les transitions de scène à scène sont affichées en orange, tandis que
les transitions de scène à objet sont affichées en bleu.

## Supprimer des objets

Cela se fait en effectuant un clic-droit sur l'objet et en sélectionnant
"Supprimer" dans le menu.
Il est aussi possible d'utiliser la touche supprimer (sous Windows ou Linux)
ou Backspace (sous Mac).
