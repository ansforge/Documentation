---
title: Création d'un projet sur Github
nav_order: 3
description: >-
  Basés sur
  https://doc.incubateur.net/communaute/gerer-sa-startup-detat-ou-de-territoires-au-quotidien/je-fais-des-choix-technologique/standards-de-qualite-beta.gouv.fr
---

# Création d'un projet sur Github

## Règle de nommage d'un projet 
 - Acronyme en début de nom pour identifier l'équipe :
> Exemple : PSC pour ProSantéConnect, SMT pour Serveur Multi-Terminologies
 - Nom de l'application ou explication de l'application de façon 'signifiante"
> Exemple : esignsante ou script-tnra-samu

Soit : psc-script-test-sandbox ou smt-ontostream

## Exigences lors de la création d'un projet
- Création d'un readme.md à la racine du projet qui décrit celui-ci.
- Ajout d'une licence à la racine du projet (MIT, etalab-2.0... [https://www.data.gouv.fr/fr/pages/legal/licences/](https://www.data.gouv.fr/fr/pages/legal/licences/) )
- Documenter l'installation si besoin : création d'un fichier install.md
- Pour la gestion des versions, privilégier le Semver : [https://semver.org/lang/fr/](https://semver.org/lang/fr/) 
- Si possible, utiliser un workflow Github pour publier des pages automatiquement (exemple : Design System)
- Activer Dependabot (ou équivalent) pour vérifier les vulnérabilités des dépendances du projet
- Faire attention aux informations sensibles (mots de passe, ip...)

## Standards de qualité logicielle 

* Le code source est **ouvert**, y compris à la contribution externe.
* Le code est instrumenté par des **tests automatisés**.
* Le code est **déployé fréquemment**, idéalement en continu.
* Le code est écrit en utilisant les **standards** du langage et des frameworks.

## Quelle langue utiliser dans le développement de mon produit ?

Tout ce qui concerne le métier (README, Pull Requests, documentation, ...) doit être écrit **en français**.
