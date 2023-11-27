+++
title = "Ce que j'ai appris en cours Github Pages - Hugo"
date = 2023-11-14T15:46:35+01:00
author = "Thanh-Long Pham"
showToc = true
TocOpen = true
+++

---

## Hugo
J'ai découvert Hugo, un framework permettant de créer des sites web static rapidement.

Initialisation : J'ai utilisé la commande ```hugo new site``` pour créer la structure de base de mon site.

Ajout de thème : Puis j'ai pu rajouter le thème du site avec ```git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke``` et ```echo "theme = 'ananke'" >> hugo.toml``` pour rajouter le thème dans le fichier de configuration.

Serveur local : En utilisant la commande ```hugo server ```, j'ai lancé un serveur local pour visualiser les changements en temps réel.

Ajout d'article : En tapant ```hugo new posts/mon-article.md```, j'ai créé un nouvel article où l'on pourra écrire en Markdown.

Personnalisation : Pour personnaliser un thème Hugo, il suffit de le surcharger, en effet Hugo utilise une hiérarchie de fichiers. Vous créez simplement un dossier nommé "layouts" dans votre site Hugo, puis vous reproduisez la structure du thème que vous voulez personnaliser à l'intérieur. Les fichiers que vous ajoutez ici remplaceront automatiquement ceux du thème original...

Build : Pour exporter le site en HTML et CSS prêts à être déployés, j'ai utilisé la commande ```hugo```. Cela a généré un répertoire "public" contenant les fichiers statiques du site.

## Git
Bien que je connaissais déjà les bases comme init, commit, add, et push, j'ai découvert une astuce géniale qui a changé la donne pour moi : la gestion de sous-répertoires.

Le cours m'a appris à créer un sous-répertoire dans le dossier /public de mon projet. Cela a rendu le processus de déploiement sur GitHub Pages super fluide et organisé.

La démarche est incroyablement simple, mais le résultat est là. GitHub Pages me permet de partager mes projets gratuitement en un instant.

## GitHub Actions
Aujourd'hui, j'ai mis en place une GitHub Action pour automatiser le processus de build et de déploiement de mon site Hugo sur GitHub Pages.

Configuration initiale : J'ai créé un fichier .yml dans le répertoire .github/workflows pour définir mes actions.

Build automatisé : Le workflow déclenche un build automatique chaque fois que je pousse du nouveau code vers ma branche principale.

Déploiement sur GitHub Pages : J'ai ajouté une étape pour déployer le site généré sur GitHub Pages.

Témoin silencieux : Les Actions GitHub fonctionnent en arrière-plan, assurant la mise à jour automatique du site.

En résumé, cette GitHub Action simplifie le processus de mise en ligne de mon site Hugo, en automatisant les tâches de build et de déploiement. Un ajout pratique pour maintenir mon site à jour sans intervention manuelle.