---
title: La Panthère
publishDate: 2023-01-10 00:00:00
img: /assets/stock-5.jpg
img_alt: image site la panthere
description: |
  Analyse et amélioration du SEO et de l'accessibilité d'un site web.
tags:
  - Référencement on-page
  - Optimisation pour les moteurs de recherche (SEO)
---

### > <a href="https://github.com/SBH2014/La-Panth-re"> La panthère</a>

> Projet 4 du parcours "Développeur web" d'OpenClassrooms - Optimisez un site web existant

### Objectif

L'objectif est d'analyser et d'optimiser (SEO et accessibilité) le site web déjà existant de l'agence web "La Chouette Agence". Puis comparer les 2 versions du site.

### Contraintes techniques

- La couleur
  - Le contraste des couleurs DOIT être conforme aux exigences du niveau AA.
  - Un contraste dont le ratio est de 4.5:1 pour les textes normaux (dont la fonte est inférieure à 18 points ou 14 points en gras) ;
  - Un contraste dont le ratio est de 3:1 pour les grands textes (18 points minimum ou 14 points en gras).
- L'information transmise par la couleur DOIT également être disponible par d'autres moyens (texte souligné pour les liens, etc.).
- La visibilité

  - Les techniques de masquage du contenu, telles que l'opacité nulle, l'ordre d'indexation en « z » et le placement hors écran, NE DOIVENT PAS être utilisées exclusivement pour gérer la visibilité.
  - Tout ce qui est autre, que l'écran actuellement visible, DOIT être vraiment invisible (particulièrement pertinent pour les apps à page unique avec plusieurs « cartes »)
  - Utilisez l'attribut hidden ou les propriétés de style visibility ou display.
  - Sauf si cela est absolument inévitable, l'attribut aria-hidden NE DOIT PAS être utilisé.

- Le focus

  - Tous les éléments activables DOIVENT être focusables : Les contrôles standard tels que les liens, les boutons et les champs de formulaire sont accessibles par défaut.Les contrôles non standard DOIVENT avoir un rôle ARIA (en-US) approprié qui leur est attribué, comme button, link ou checkbox.

  - Le focus DOIT être traité dans un ordre logique et de manière cohérente.

- Les équivalents textuels

  - Un équivalent textuel DOIT être fourni pour chaque élément non textuel non strictement présenté dans l'application.

  - Utilisez alt et title lorsque cela est approprié (voir l'article de Steve Faulkner sur l'Utilisation de l'attribut HTML title).
  - Si les attributs ci-dessus ne sont pas applicables, utilisez les États et propriétés ARIA appropriés tels que aria-label, aria-labelledby, ou aria-describedby.
  - Les images de texte DOIVENT être évitées.
  - Tous les composants de l'interface utilisateur ayant un texte visible (ou une image de texte) comme étiquette DOIVENT avoir le même texte disponible dans le nom programmatique du composant.

- La gestion des états

  - Les contrôles standard tels que les boutons radio et les cases à cocher sont gérés par le système d'exploitation. Cependant, pour d'autres contrôles personnalisés, les changements d'état DOIVENT être fournis via les états ARIA tels que aria-checked, aria-disabled, aria-selected, aria-expanded et aria-pressed.

- L'orientation

  - Le contenu NE DOIT PAS être limité à une seule orientation, comme le portrait ou le paysage, sauf si cela est essentiel.

### Compétences évaluées

- Réaliser une recherche des bonnes pratiques en développement web
- Assurer l'accessibilité d'un site web
- Écrire un code HTML et CSS maintenable
- Optimiser la taille et la vitesse d’un site web
- Optimiser le référencement d'un site web
