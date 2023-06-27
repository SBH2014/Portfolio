---
title: API Piiquante
publishDate: 2022-11-12 00:00:00
img: /assets/stock-6.jpg
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  Construire une API sécurisée
tags:
  - Express
  - Node
  - MongoDB
---

> <a href="https://github.com/SBH2014/PIIQUANTE">Piiquante</a>

> Projet-6 : Construisez une API sécurisée pour une application d'avis gastronomiques

### Objectif

Développement d'une application web nommée "Piquante" dans laquelle les utilisateurs pourront ajouter leurs sauces préférées et liker ou disliker les sauces proposées par les autres utilisateurs. Le but est de créer le backend de l'application, le frontend étant déjà codé et fourni.

### Contraintes techniques

- Composition du site
  - Une page de connexion ou d'inscription
  - Une page d'accueil
  - Une page descriptive pour chaque sauce à noter
  - Une page création de sauce
- Page d'inscription / de connexion
  - Dans un premier temps, l'utilisateur arrive sur une page d'inscription ou de connexion sécurisée : son email et son mot de passe sont enregistrés de façon cryptés dans la base de données Mongo DB.
- La page d'accueil
  - Une fois authentiflié, l'utilisateur est dirigé sur la page d'accueil qui présente les différentes sauces créées par les utilisateurs.
- Les pages produits
  - Une page produit affiche les informations précises de la sauce.
  - L'application offre la possibilité d'ajouter un "like" ou un "dislike" à la sauce.
- La page d'ajout de sauce
  - L'utilisateur peut également créer une nouvelle sauce. Pour plus de sécurité, il ne pourra supprimer ou modifier que les sauces qu'il a lui-même créé.

### Compétences acquises

- Implémenter un modèle logique de données conformément à la réglementation
- Stocker des données de manière sécurisée
- Mettre en œuvre des opérations CRUD de manière sécurisée
