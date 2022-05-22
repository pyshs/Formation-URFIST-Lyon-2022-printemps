## Python pour les SHS - URFIST Lyon - 24 mai 2022

Description de la séance : [ICI](https://sygefor.reseau-urfist.fr/#/training/9582/11267](https://sygefor.reseau-urfist.fr/#/training/8972/11331)

La séance de 6 heures en **présentiel** couvre :

- les bases du langage Python et de son environnement (en particulier le Notebook Jupyter)
- l'installation et la recherche de bibliothèques
- l'utilisation de la bibliothèque Pandas pour manipuler des données + statistiques
- des exemples d'usages un peu plus avancés

(cela correspond aux chapitre 2 à 5 du Manuel Python pour les SHS)

Les documents dans le dépôt correspondent à la formation (mis à jour à la fin), en particulier les supports montrés et les notebooks associés.

Pour toute question suite à la formation, ne pas hésiter à contacter emilien.schultz[at]ird.fr

### Rapide panorama

Python est un langage interprété qui nécessite un environnement. 

Il existe plusieurs manières de l'utiliser :

- Sur votre ordinateur, avec Anaconda (ci-dessous)
- Sur le Cloud, avec différentes solutions, par exemple Google colab https://colab.research.google.com/

Le Cloud est une solution souple qui évite l'installation mais rend plus difficile l'importation de données.

### Installation d'Anaconda

Anaconda est un environnement qui fournit l'ensemble des éléments nécessaires pour exécuter du code python. Il permet de construire des environnements (une version du langage et de librairies spécifiques) et de travailler au sein de ces environnements permettant d'en avoir plusieurs (par exemple, pour tester des versions différentes de librairies, etc.)

- Télécharger Anaconda pour votre OS : https://www.anaconda.com/distribution/
- Installer (suivant que vous soyez sous Windows, Linux ou Mac, la procédure va changer)
- Lancer Anaconda pour créer un environnement de travail
  - Sur windows : Aller dans environnements > Create > donner un nom (ex. p38) et une version de python 3.8 (__Attention bien installer la version 3.7 ou plus de Python __)
  - Sur linux/mac : Ouvrir un terminal, puis créer un environnement en tappant la commande : conda create --name p38 python=3.8 (pour toute information sur les commandes conda : https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
- Lancez l'environnement (sur Windows en lançant Anaconda ; sous linux/mac en tapant la commande source activate p39 dans un terminal)

Autres logiciels: vous pouvez installer Sublime text : https://www.sublimetext.com/ (pour manipuler des documents textes)

