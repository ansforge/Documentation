---
title: Bien commencer
nav_order: 2
description: 
---

# Bien commencer

## Pourquoi Github ?

Github permet de diffuser publiquement :
- du code source
- des nomenclatures
- des modélisations FHIR
- ...

## Premiers pas sur Github 

Les différents projets de l'ANS sur Github sont publics.
Pour pouvoir modifier un projet via une pull request, il vous faut donc créer un compte. Ce compte doit refléter votre identité et avoir une connexion multifacteurs pour sécuriser les accès.

Pour plus d'informations, suivre la documentation présente sur [cette page 🧭](../docs/github.md)

Pour pouvoir être reconnu dans l'organisation, merci d'envoyer un mail à `ans-forge@esante.gouv.fr`

## Création d'un projet sur Github

Plusieurs exigences doivent être respectées :
- Création d'un readme.md à la racine du projet qui décrit celui-ci.
- Ajout d'une licence à la racine du projet (MIT, etalab-2.0... [https://www.data.gouv.fr/fr/pages/legal/licences/](https://www.data.gouv.fr/fr/pages/legal/licences/) )
- Documenter l'installation si besoin : création d'un fichier install.md
- Pour la gestion des versions, privilégier le Semver : [https://semver.org/lang/fr/](https://semver.org/lang/fr/) 
- Si possible, utiliser un workflow Github pour publier des pages automatiquement (exemple : Design System)
- Activer Dependabot (ou équivalent) pour vérifier les vulnérabilités des dépendances du projet
- Faire attention aux informations sensibles (mots de passe, ip...)


## Création d'une équipe sur Github

Il est possible de créer des équipes sur Github ayant des droits spécifiques sur les projets.
La création d'une équipe est du type [Organisation] / [Nom du programme].
Pour créer une équipe dans l'organisation ANS, merci d'envoyer un mail à `ans-forge@esante.gouv.fr` avec les informations demandées.
