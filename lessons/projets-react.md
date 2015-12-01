# Projets

**Je souhaite que tout le code que vous soumettez soit votre propre création, si ce n'est pas le cas,
il est obligatoire de le spécifier explicitement en incluant les liens vers les parties reprises en haut de chacun des fichiers repris.**

Voici une liste des projets react.js que je vous propose

## Lecteur de GIST (Entrainement)

Le but de ce petit projet est d'afficher le dernier GIST pour un utilisateur donné : Par exemple, voici la liste des gist de l'utilisateur TJ : https://gist.github.com/tj

On souhaite utiliser l'API de github pour récupérer ces données sur notre page web.
L'url a utiliser pour l'API est https://api.github.com/users/:username/gists

Il faut pouvoir :

 * Entrer un nom d'utilisateur dans un champ texte.
 * Cliquer sur "get last gist" pour récupérer le dernier gist
 * On a alors un lien qui apparait en résultat sur une liste
 * On peut cliquer sur le lien qui dirige vers le gist

## Morpion (Entrainement)

  * Affichage du jeu
  * Interaction avec la souris (Jeu 2 joueurs)
  * Jeu sur deux ordinateurs différents (avec un serveur)
  * Intelligence artificielle

## Vote pour une image parmi deux, jusqu'a trouver la meilleure (Entrainement)

Le logiciel est initialisé avec plusieurs images (coté serveur).
On affiche à chacun des clients web deux images prises aléatoirement.
L'utilisateur clique sur celle qu'il préfère, ce qui met à jour le score des deux images.
Le but est d'arriver à faire classer les images par plusieurs personnes simultanément.

Il faut également avoir une vue qui permette d'afficher toutes les images classées par score.

## Client de Poker

 * Affichage du jeu
 * Il ne faut pas faire tout le moteur de jeu ici, on utilisera des librairies existantes : https://github.com/mdp/JsPoker, https://github.com/mdp/MachinePoker, https://github.com/mdp/binions, https://github.com/mdp/hoyle
 * Communication avec un serveur
 * Jeu multijoueur, sur plusieurs ordinateurs
 * Jeu contre une IA
 * Sauvegarde du log du jeu (format Pokerstars)

## Clone de 2048

 * Affichage du jeu
 * Moteur du jeu
 * Interaction (clic souris, touches clavier)
 * Animations
 * Sauvegarde/Chargement de partie sur un serveur
 * Sauvegarde du score / tableau highscore, partage facebook et twitter
 * Version natives iPhone et Android avec ReactNative

## Email Client

 * API d'envoi de mail qui s'interface avec https://github.com/mscdex/node-imap
 * Affichage des mails
 * Créer un nouveau mail
 * Envoi de mail
 * Ajout de PJ avec Drag&Drop
 * Trier ses mails (avec les dossiers IMAP)
 * Recherche dans ses mails

## Conway's Game of Life

<a href="https://en.wikipedia.org/wiki/Conway's_Game_of_Life">Lien explication game of life</a>

 * Affichage du jeu
 * Moteur du jeu
 * Réglage de la vitesse / taille des cases
 * Interaction (play/pause / retour dans le temps, avec la souris ou le clavier)
 * Sauvegarde/Chargement de partie sur un serveur
 * Changement des règles par une interface
 * Pièces ajoutables : Block,Beehive,Loaf,Boat , Blinker, Toad, Beacon, Pulsar, Pentadecathlon, Glider, Lightweight spaceship (LWSS) (Venant du serveur également)
 * Version natives iPhone et Android avec ReactNative

## Tetris

 * Affichage du jeu
 * Moteur du jeu
 * Interaction (avec la souris ou le clavier)
 * Score / Highscore, partage facebook et twitter
 * Niveaux de jeux
 * Version natives iPhone et Android avec ReactNative

## Checklist pour proposer votre propre projet :

 * Doit avoir une UI HTML écrite en React conséquente. L'UI doit être dynamique
 * Doit avoir un serveur écrit en Node.JS, avec express
 * Déployable avec un simple `git push` (en utilisant heroku)
 * Le projet doit être suffisamment complexe

