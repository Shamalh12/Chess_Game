Présentation de "JeuEchecPravine", un simple programme d'échecs en Python fonctionnant en ligne de commande. Vous pouvez jouer une partie complète contre lui.
Exécutez-le avec la commande : ./main.py

Il prend actuellement en charge :

la promotion
la sous-promotion
la prise "en passant"
Les commandes sont les suivantes :

new pour commencer une nouvelle partie
e2e4 ou e7e8q par exemple pour déplacer une pièce. Les promotions sont q,r,n,b pour la dame, la tour, le cavalier, le fou
undomove pour annuler le dernier mouvement
legalmoves pour afficher les mouvements légaux pour le camp qui doit jouer
go demande au moteur de jouer maintenant
setboard fen pour définir la position du plateau comme la position FEN donnée
getboard pour exporter la position FEN actuelle
sd x pour définir la profondeur de recherche
perft x pour tester le générateur de mouvements (x = profondeur de recherche)
quit... pour quitter
Choses à faire :

ordonnancement des mouvements

règle des 50 coups
règle des 3 répétitions
réglages de temps
livre d'ouvertures
Exigences :

Python 3
