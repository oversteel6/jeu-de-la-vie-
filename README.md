# jeu-de-la-vie-avec-une-fractale

salut,je m'appelle Aly kane ,j'ai 17ans et je participe au jeu concours pour l'integration du jeu de la vie 
je passe le bacc en s2 et reve de devenir ingenieur en robotique , je tiens à préciser que je ne suis pas du tout développeur et j'ai beaucoup eu a utilise YouTube comme support 
Neammoins étant donné que Python est le seul langage de programmation que je maîtrise, j'ai été dans l'obligation d'utiliser Python dans ce projet

voici une presentation ci dessous de comment fonctionne mon code:
Ce code utilise la bibliothèque Pygame pour simuler le "Jeu de la Vie" de Conway avec une représentation graphique simple et une fractale basique. Le "Jeu de la Vie" est un automate cellulaire, une simulation de cellules vivantes et mortes selon des règles spécifiques.
Constantes
GRID_SIZE:renseigne la taille des cellules dans la grille.
WHITE et BLACK: aont les couleurs utilisées dans la représentation graphique.
Initialisation
init_grid(): Initialise aléatoirement la grille de cellules avec les valeurs 0 ou 1, correspondant à l'etat mort ou vivant, respectivement.
update_grid(grid): qui applique les règles du "Jeu de la Vie" pour mettre à jour l'état de la grille en fonction de l'état actuel des cellules et de leurs voisins.
draw(grid): quant à elle dessine la grille de cellules et une fractale simple (ici, un rectangle blanc) à l'aide de Pygame.
Boucle Principale (main())
Initialise la fenêtre Pygame et la grille.
La boucle principale exécute les étapes suivantes :
Gère les événements Pygame, tels que la fermeture de la fenêtre.
Met à jour la grille selon les règles du "Jeu de la Vie".
Dessine la grille mise à jour.
Ajuste la vitesse du jeu avec clock.tick(10).
Au lancement, la simulation démarre avec une grille aléatoire,qui forme une fractale simple en fin
Les cellules évoluent selon les règles du "Jeu de la Vie" à chaque itération.
Pour quitter la simulation,on doit fermez la fenêtre.
