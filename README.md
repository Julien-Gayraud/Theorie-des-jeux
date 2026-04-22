# Recherche numérique des équilibres de Nash

réalisé en collaboration avec Chloé Dubouchet et 
encadré par De Gournay Frédéric et Duboscq Romain
à l'INSA Toulouse

Le but de ce projet est de présenter une manière de trouver les équilibres de Nash pour les jeux finis. D'après le Théorème de Nash, nous savons que de tels equilibres mixtes existent, l'objectif est donc de trouver ces stratégies numériquement.

Le rapport est en cours de rédaction. Le développement de notre objet python pour chercher ces équilibres est terminé.

Le rapport présentera le travail effecté et des preuves théoriques sur la construction et la régularité de notre fonction de regret et sur les limites de notre algorithme. 

L'objet python `GameMinizer` peut chercher les équilibres de Nash pour tout jeu à **n** joueurs avec un nombre d'actions pures fini pour chaque joueur.
Notre objet python cherche les équilibres de Nash en minimisant une **Fonction de regret F** construite de telle façon que ses minimums globaux, atteints lorsque **F=0**, soient les équilibres recherchés. Finalement, nous avons analysé les limites de notre algorithme en présentants des jeux où l'algorithme ne converge que vers un minimum local ou point selle.
