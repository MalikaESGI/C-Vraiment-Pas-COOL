Ce jeu Bomberman est une implémentation interactive pour deux joueurs. Chaque joueur se déplace sur une carte, pose des bombes pour détruire des obstacles et tente d'éliminer l'adversaire. Le jeu se termine quand un joueur est éliminé ou, si aucun joueur n'est éliminé, le vainqueur est déterminé par un ratio de destruction.

Commandes de Jeu:

    Joueur 1 (Clavier QWERTY):
        Up, Down, Right, Left pour se déplacer.
        M pour poser une bombe.
    Joueur 2 (Clavier QWERTY):
        W, A, S, D pour se déplacer.
        R pour poser une bombe.

Objectif du Jeu:
Le jeu se termine lorsqu'un joueur est touché par une explosion. En cas de non élimination, le vainqueur est déterminé par le ratio du nombre d'obstacles détruits par le nombre de bombes utilisées.

Fonctions Principales:

    Charger la Carte (chargerCarte):
        Lit et stocke les données d'une carte de jeu à partir d'un fichier texte dans un tableau 2D.
    Jouer (jouer):
        Gère la boucle principale du jeu (démarrage, en cours, fin).
    Déplacer Joueur (deplacerJoueur):
        Gère le déplacement des joueurs et les collisions.
    Création de Bombe (creerBombe):
        Permet de poser des bombes qui exploseront après un délai.
    Gestion de Bombe (gererBombe):
        Contrôle le compte à rebours et les effets des explosions.
    Placement Aléatoire d'Obstacles (placementAleatoireObstacle):
        Génère aléatoirement des obstacles destructibles.

Gestion des Threads:

    Utilisation de threads pour la gestion simultanée des entrées des joueurs et une réponse rapide aux actions.
