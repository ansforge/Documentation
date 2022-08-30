Documentation sur le Github de l'ANS

Ce projet a été pensé pour être distribué au travers de Github pages. Il utilise Jekyll qui est supporté par Github. 

Le projet Jekyll se trouve dans le dossier docs/.

# Développement

Pour lancer le projet localement, allez dans le dossier docs/ puis lancez la commande `bundle exec jekyll serve`.

Le site sera accessible sur l'url : `http://localhost:4000/docs/`.

# Rédaction 

Pour rédiger de la documentation, vous pouvez créer / modifier les fichier .md (markdown) dans le dossier "docs/pages/". 

Répertoires: 

* documentation: documentation générale ressource par ressource
* quick-start: section regroupant la documentation de démarrage rapide
* use-cases: section qui contient des tutoriaux complets basés sur des uses cases

# Menu 

Le menu du haut est géré avec le fichier _data/menu.yml. Quand vous ajoutez une nouvelle partie, il faut la renseigner dans le menu.yml pour la voir apparaitre. 


# Publication (déploiement)

Pour mettre en ligne, publiez le projet sur un projet GitHub et dans la section "Settings > Pages", activez la fonctionnalité Github pages. 

Dans la version gratuite de Github, vous devez mettre le projet public pour que cela fonctionne. 

