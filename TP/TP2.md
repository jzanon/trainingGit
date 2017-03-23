# TP2 : Création et initialisation d'un dépôt. Utilisation de l'outil de visualisation Gitk

Le but de ce TP est de découvrir la notion de dépôt, et de le parcourir via un outil graphique


## Création d'un dépot local depuis un dépôt distant

Pour récupérer un dépôt distant et son contenu, et créer un dépôt local, on utilise la commande git clone

    git clone https://github.com/(...)/git-training.git

Inspecter le dossier créé dans votre dossier courant. Inspecter le sous dossier .git de celui-ci et son contenu

Afficher et inspecter l'historique avec 

    gitk


## Création d'un dépôt local

* Créer un nouveau répertoire dans le dossier utilisateur, y ouvrir un terminal
* Initialiser un dépôt
* Créer plusieurs fichiers texte, avec du contenu

## Création du premier commit

* On ajoute les fichiers à l'index, puis on "commit"


	git add --all
	
	git commit -m "Mon premier commit"

* Lire l'historique des commits avec la commande 


    git log


## Visualisation du dépôt avec gitk

* Dans le répertoire du dépôt, lancer la commande gitk
* Parcourir le dépôt avec l'interface graphique
* Repérer les actions clés de l'interface


## Répéter les mêmes opérations depuis gitk

* Récupération d'un dépôt distant
* Initialisation d'un dépôt local vide





