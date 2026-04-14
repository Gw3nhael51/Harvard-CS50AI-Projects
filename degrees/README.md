## Project: Six Degrees (CS50 AI)

### Description
Ce projet implémente un algorithme de recherche pour trouver le plus court chemin entre deux acteurs en fonction des films dans lesquels ils ont joué ensemble. C'est une application concrète de la théorie des graphes et des algorithmes de recherche en intelligence artificielle.

### Concepts Clés
* **Breadth-First Search (BFS)** : Utilisation d'une recherche en largeur pour garantir l'obtention du chemin le plus court (le nombre minimal de degrés de séparation).
* **Gestion des Graphes** : Les acteurs sont des nœuds et les films sont des arêtes.
* **Structures de Données** : Utilisation de files (Queues) pour la frontière et d'ensembles (Sets) pour optimiser la vérification des états déjà explorés.

### Stack:
* **Langage** : Python 3.12
* **Data** : Parsing de fichiers CSV volumineux (IMDb datasets).
* **OS** : Développé et testé sous Ubuntu 24.04.

### Comment ça marche ?
L'IA explore le réseau social du cinéma couche par couche. Pour chaque acteur, elle identifie tous ses partenaires de jeu jusqu'à ce qu'elle atteigne la cible, puis elle remonte la chaîne des "parents" pour reconstruire l'itinéraire exact.

### Note sur la confidentialité (Academic Honesty)
Conformément à la politique d'honnêteté académique du cursus **CS50 de l'Université Harvard**, le code source de ce projet n'est pas publié en accès libre. En tant que solution à un exercice académique, sa diffusion publique est restreinte afin de préserver l'intégrité du parcours pour les futurs étudiants. 

[Lien du programme](https://shorturl.at/U2CDO)

# Screen Output small csv

![Tester l'algo avec le small csv](/assets/image.png)

# Screen output large csv

![Tester l'algo avec le larg csv](/assets/image-1.png)

# Ecran de verification de l'exercice

![Envyer la requete de verification de l'exercice aux serveurs](/assets/serveur_recu.png)

# Steps correction

![Test unitaire avec check50](/assets/check50.png)