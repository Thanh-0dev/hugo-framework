+++
title = 'Github actions'
date = 2023-11-14T15:46:35+01:00
weight = 2
+++

Aujourd'hui, j'ai mis en place une GitHub Action pour automatiser le processus de build et de déploiement de mon site Hugo sur GitHub Pages.

Configuration initiale : J'ai créé un fichier .yml dans le répertoire .github/workflows pour définir mes actions.

Build automatisé : Le workflow déclenche un build automatique chaque fois que je pousse du nouveau code vers ma branche principale.

Déploiement sur GitHub Pages : J'ai ajouté une étape pour déployer le site généré sur GitHub Pages.

Témoin silencieux : Les Actions GitHub fonctionnent en arrière-plan, assurant la mise à jour automatique du site.

En résumé, cette GitHub Action simplifie le processus de mise en ligne de mon site Hugo, en automatisant les tâches de build et de déploiement. Un ajout pratique pour maintenir mon site à jour sans intervention manuelle.