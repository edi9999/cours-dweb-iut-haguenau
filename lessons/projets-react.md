# Projets

**Je souhaite que tout le code que vous soumettez soit votre propre création, si ce n'est pas le cas,
il est obligatoire de le spécifier explicitement en incluant les liens vers les parties reprises en haut de chacun des fichiers repris.**

Voici une liste des projets react.js que je vous propose

### Application de messagerie instantanée à la messenger.com

Joel Mercier (@Joel-Mercier) & François Mang (@Franz9425) : 

 - Discussion en temps réel avec une autre personne avec gestion des notifications lors d'un nouveau message 
 - Discussions de groupe
 - Historique des messages 
 - Eventuellement portage sur React Native
 - Envoi de texte formaté en markdown
 - Travailler sur une intégration avec d'autres outils (par exemple, avec github, pour avoir une notification quand quelqu'un fait un commit (ou une autre intégration))


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

Quentin Kerguélen (@qkerguelen) et Hugo Beyer (@HugoBeyer67)

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


## Memory
Alexis Smouts (@Pappum) et Antoine Waag (@waagou)

 * Affichage du jeu
 * Moteur du jeu
 * Score / Highscore, partage facebook et twitter
 * Niveaux de jeux
 * Sauvegarde
 * Version natives iPhone et Android avec ReactNative
 * Mode multijoueur sur deux ordinateurs avec un serveur
 * Le mode multijoueur doit pouvoir marcher avec autant de joueurs que l'on souhaite

## Checklist pour proposer votre propre projet :

 * Doit avoir une UI HTML écrite en React conséquente. L'UI doit être dynamique
 * Doit avoir un serveur écrit en Node.JS, avec express
 * Déployable avec un simple `git push` (en utilisant heroku)
 * Le projet doit être suffisamment complexe
 
## Jeu 2 joueurs 1 contre 1
@ZussyFranck

* Génération d’un terrain
* Contrôle des déplacement des deux personnages
* Gestion des collisions avec le terrain et entre les personnages
* Gestion des attaques des personnages
* Possibilité de jouer en ligne un contre un pour la partie serveur
* Ajout de bonus générés aléatoirement sur le terrain (à voir)


