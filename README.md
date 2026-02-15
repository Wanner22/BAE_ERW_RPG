# BAE_ERW_RPG
## RPG Project on Unreal Engine 5

### Dans ce prototype :
#### - Environnement : Village, château, petite zone ouverte
#### - Combats et IA : Ennemis aggressifs
#### - Inventaire : Sorts, items, consommables à ramasser ou acheter
#### - Économie : Argent à dépenser pour acheter des items dans la boutique

|Action|Input|
|---|---|
|Déplacements|CLick gauche sur l'environnement|
|Interagir|E|
|Utiliser l'objet équipé|F|
|Ouvrir l'inventaire|Tab/I|
|Zoomer/Dézoomer|Molette Haut/Bas|

Difficultés :
- L'UI du joueur apparaissait sur l'écran titre et j'ai pas trouvé d'autre solution que de mettre un tick qui dit que si l'UI du joueur existe et qu'il est visible, tu le caches. C'est pas opti mais c'est la seule solution que j'ai trouvé

- J'ai essayé de faire en sorte que quand un objet est proche de la caméra, il devient transparent. J'ai réussi ça mais le Hit du click reste sur l'objet devant la caméra donc ça empêche le joueur de bouger. Donc j'ai fait une box qui change la caméra quand elle détecte le joueur pour faciliter les déplacements
