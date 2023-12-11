## Règles du Jeu

## Mise en Place


Plateau de Jeu : Chaque joueur (bot) dispose d'un plateau 10x10 pour placer ses navires et deviner les positions ennemies.
Navires : La flotte de chaque joueur comprend :
1 porte-avions (5 cases)
1 croiseur (4 cases)
2 contre-torpilleurs (3 cases chacun)
1 torpilleur (2 cases)
Tour de Jeu : Les bots jouent à tour de rôle, bombardant une case à la fois. Les réponses aux tirs (touché, manqué, coulé) sont communiquées après chaque tir.
Fin de la Partie : Le jeu se termine lorsque tous les navires de l'un des bots sont coulés.

## Règles Supplémentaires


Mines : Des mines sont placées secrètement. Si un bot tire sur une mine, il perd son prochain tour.
Radar : Une fois par partie, un bot peut scanner une zone 3x3 pour détecter la présence de navires sans connaître leurs positions exactes.
Frappe nucléaire : Une fois par partie, un bot peut effectuer un tir sur une zone 3x3.
Tir en Rafale : Une fois par partie, un bot peut effectuer un tir sur 3 cases consécutives.
Frappe Aérienne : Chaque bot dispose d'une frappe aérienne pour bombarder une ligne ou colonne entière. Utilisable une seule fois.
Système de Défense : Deux navires par flotte sont équipés d'un système de défense, les protégeant du premier tir.
Sous-marin de Reconnaissance : Permet de détecter la présence de navires ennemis sur une ligne ou une colonne donnée.

## Déroulé de la partie

Les joueurs sont répartis dans l'ordre d'arrivée. Chaque joueur affronte le prochain dans un duel, à tour de rôle (le dernier joueur affronte le premier). Si un joueur n'a plus de carte, il perd la partie et ne peut plus joueur.

### Déroulé des duels

* Lors d'un duel, chacun de joueur joue une carte de sa pile. Le joueur ayant joué la carte de plus haute valeur l'emporte et met sous sa pile les cartes jouées, en les mélangeant.
* Si les deux joueurs ont joué une carte de même valeur, le duel recommence en accumulant les cartes jouées de telle sorte à ce que le gagnant empoche la totalité des cartes du duel.

## Fin de la partie

Le gagnant est le dernier joueur en lice.

### Détail des classes principales

Un exemple de jeu supportant le réseau

* LocalWarGame la version du jeu supportant le jeu en local
* WarGameEngine le moteur du jeu
* WarGameNetorkPlayer le joueur distant en cas de partie réseau
* WarGameNetworkEngine la version du jeu supportant le réseau





