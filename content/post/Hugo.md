+++
title = 'Hugo'
date = 2023-11-14T15:46:35+01:00
weight = 1
+++

Aujourd'hui, j'ai découvert Hugo, un framework permettant de créer des sites web rapidement.

Initialisation : J'ai utilisé la commande hugo new site pour créer la structure de base de mon site.

Ajout de thème : Puis j'ai pu rajouter le thème du site avec "git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke" et "echo "theme = 'ananke'" >> hugo.toml" pour rajouter le thème dans le fichier de configuration.

Serveur local : En utilisant la commande hugo server -D, j'ai lancé un serveur local pour visualiser les changements en temps réel.

Ajout d'article : En tapant hugo new posts/mon-article.md, j'ai créé un nouvel article et sa structure en Markdown.

Personnalisation : J'ai personnalisé le site en modifiant le code et en ajustant les paramètres, ajoutant ainsi ma touche personnelle.

Build : Pour exporter le site en HTML et CSS prêts à être déployés, j'ai utilisé la commande hugo. Cela a généré un répertoire "public" contenant les fichiers statiques du site.

En résumé, Hugo s'est avéré être un outil pratique pour simplifier le processus de création de sites web, offrant une approche directe et efficace.




