# DCuniverse
L’objectif de ce projet est le développement d’un jeu vidéo sûr en Haskell. Le jeu est en 2d
et a pour thème l’univers du Donjon Crawling. A l’aide de différentes ressources, que ce soit
la bibliothèque SDL2 ou encore des tileset libre de droits, nous avons mis en place un Donjon
Crawler utilisant une boucle non-réactive.

# Outils d'installation 
- Installer Haskell : https://docs.haskellstack.org/en/stable/README/
- Installer SDL2  
- Installer la librairie ttf pour les fonts. (sous ubuntu : sudo apt-get install libsdl-ttf2.0-dev )
- Lancer le jeu en faisant `stack run` à la racine du repertoire
- Pour lancer les test, utiliser `stack test`

# Instructions In-Game
- Voir le rapport

## Avancement

- Generation de la map depuis un fichier

- Deplacement du personnage avec direction

- Collision avec les entités

- Ouverture de portes/coffres

- Systeme de vie

- Activation de pieges qui enlevent de la vie

- Coffres qui rendent de la vie

- Fin de jeu lorsque l'on sors

- Menu de jeu pour débuter ou relancer

- IA de mob basique

## Invariants

Pour le generateur de labyrinthe :

- Objets dans la map (pas en dehors)

- entrée et sortie unique

- porte entre deux murs
