# TP4 : Les principales commandes GIT de gestion des branches (création, fusion, comparaison).

Le but de ce TP est de comprendre et d'utiliser les principales commandes de GIT pour la gestion des branches. 

On utilisera le dépôt créé lors du TP2 et TP3 pour réaliser cet exercice

## Création d'une première branche

* Depuis la branche principale, créer une branche "branche1"
* Y faire une modification (sur un des fichiers), puis "commiter" cette modification
* Retourner sur la branche principale

## Création d'une deuxième branche

* Créer une autre branche "branche2"
* Y faire une autre modification (autre fichier ou autre ligne), puis "commiter"
* Retourner sur la branche principale

## Comparaison des changements

Deux méthodes de comparaison

* Repérer les changements entre les branches via l'outil graphique gitk
* Faire la même opération avec ligne de commande

## Fusion des branches "branche1" et "branche2" dans la branche principale

Faire la fusion de branche1 dans master, puis branche2 dans master, avec la commande git merge

Il ne devrait pas y avoir de conflits si vous n'avez pas édité la même ligne dans un même fichier.

## Création de conflit

* Supprimez vos branches branche1 et branche2, puis re-créez les.
* Recommencez tout le processus, en modifiant le même fichier, même ligne dans les 2 branches

## Résolution des conflits

Ouvrez les fichiers en conflits pour les résoudre. Il faudra choisir entre les modifications apportées par la branche1, ou celles apportées par la branche2, ou bien choisir un autre contenu.

