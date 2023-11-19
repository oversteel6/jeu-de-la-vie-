# jeu-de-la-vie-avec-une-fractale
Ce code utilise la bibliothèque Pygame pour simuler le "Jeu de la Vie" de Conway avec une représentation graphique simple et une fractale basique. Le "Jeu de la Vie" est un automate cellulaire, une simulation de cellules vivantes et mortes selon des règles spécifiques.
Constantes
GRID_SIZE: La taille des cellules dans la grille.
WHITE et BLACK: Les couleurs utilisées dans la représentation graphique.
Initialisation
init_grid(): Initialise aléatoirement la grille de cellules avec des valeurs 0 ou 1, correspondant à mort ou vivant, respectivement.
Mise à Jour de la Grille
update_grid(grid): Applique les règles du "Jeu de la Vie" pour mettre à jour l'état de la grille en fonction de l'état actuel des cellules et de leurs voisins.
Affichage
draw(grid): Dessine la grille de cellules et une fractale simple (ici, un rectangle blanc) à l'aide de Pygame.
Boucle Principale (main())
Initialise la fenêtre Pygame et la grille.
La boucle principale exécute les étapes suivantes :
Gère les événements Pygame, tels que la fermeture de la fenêtre.
Met à jour la grille selon les règles du "Jeu de la Vie".
Dessine la grille mise à jour.
Ajuste la vitesse du jeu avec clock.tick(10).
Utilisation
Au lancement, la simulation démarre avec une grille aléatoire.
Les cellules évoluent selon les règles du "Jeu de la Vie" à chaque itération.
Pour quitter la simulation,on doit fermez la fenêtre.
