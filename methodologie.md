---
layout: methodologie
---
# Introduction

L'objectif final de ce classement est de permettre à des travailleurs nomades de s'implanter (à court ou long terme) dans des lieux adaptés à leurs besoins, en France. Nomadlist & d'autres font un très bon travail pour couvrir les villes internationales, mais nous restons confrontés à une problématique : pour être résident fiscal français, et donc ne pas avoir d'ennuis ou de complications fiscales, il nous faut résider pendant environ 6 mois par ans en France. Dés lors, où devons-nous nous établir ?

Remote France utilise des sources ouvertes afin d'alimenter un algorythme qui note chacune des charactéristiques des villes, et permet ainsi d'obtenir un classement cohérent et objectif.

# Présentation des catégories
## Loyer
Le loyer est un critère très important. Nous calculons le loyer mensuel médian pour un appartement ou une maison avec une chambre, et une à deux pièces. L'idée est de savoir combien cela vous coûterait de vivre seul ou en couple dans la ville visée.


## Animation
Une ville animée, c'est une ville où il fait bon vivre, où l'on peut sortir et faire des rencontres. La note animation donne donc une idée de l'activité de la ville. Elle utilise le nombre de bars et restaurants dans la ville, ainsi que la proportion d'étudiants. La proportion d'étudiants peut être supérieure à 100%, dans le cas où de nombreux étudiants seraient enrollés dans les universités de la ville, mais résideraient en périphérie, par exemple.

## Sécurité
La limite du critère des loyers est que des endroits franchement peu accueillant, et avec une ambiance menaçante peuvent tirer leur épingle du jeu. La note se sécurité permet de contrôler ce paramètre en plombant les villes avec un taux de délinquance élevé.

## Internet
Nous mesurons deux choses, qui sont toutes deux utiles pour nous autres remote workers : 
* La qualité du réseau téléphonique, et en particulier la couverture 4G
* la qualité du réseau fixe, et en particulier le taux de couverture fibre et les débits moyens

Ces deux critères, réunis dans la catégorie "Internet", permettent de s'assurer que la ville que nous choisirons a une infrastructure sufisante en place pour nous permettre de travailler dans de bonnes conditions. Et aussi, de regarder Netflix & jouer à nos jeux vidéos confortablement !

## Météo
Beau et chaud > pluvieux et froid. Certes, ça dépend des goûts, mais nous suivons pour l'instant le consensus. Les villes avec le moins de précipitations et les plus hautes températures l'emportent donc.
Nous ajoutons en outre un bonus aux villes proches de la montagne ou de la mer. Ces éléments naturels permettent en effet de se consoler du temps maussade. En particulier de la température basse quand on est à la montage (Ski, yey !)

## Transports
Pouvoir se déplacer facilement, et si possible sans voiture, est un critère quasi-éliminatoire pour beaucoup d'entres nous. Sinon, nous pourrionns nous installer dans un vieux corps de ferme en rase campagne ! Nous y viendrons peut-être, mais en attendant de pouvoir nous couper un peu plus du monde, nous favorisons les villes avec une infrastructure de transports bien en place, en particulier permettant de joindre d'autres villes facilement, en avion ou en train.

## Coworkings
Travailler à la maison, ce n'est pas pour tous le monde. D'ailleurs, ce n'est pas pour moi, je préfère de loin les coworkings ! Les villes avec le plus grand nombre de coworkings finissent avec le plus de point sur ce classement, pour vous permettre d'identifier rapidement où ce sera le plus facile de trouver une place ! A noter, les prix sont remarquablement uniformes à travers la France : 160-250€ pour un poste fixe avec accès 24/7 est la norme partout en France, sauf à paris où il faut compter une centaine d'euros de plus pour le même service (eh oui, les coworkings doivent payer un loyer ou rembourser leur emprunt !)

# Les sources
Nous utilisons uniquement des sources ouvertes. Les informations sont récupérées grâce à des scrapers, et sont aggrégées par un algorythme. Très franchement, nous sommes tentés de parler d'IA. C'est super intelligent de collecter de l'information d'un nombre de sources limitées, et de les aggréger toujours de la même manière, non ? C'est même du Machine Learning, que dis-je du Deep Learning ! On se sert même d'une Blockch... Sorry j'en peux plus il est trois heures du mat.

Plus sérieusement, nos sources sont principalements des données fournies par le gouvernement français via les initiatives 'Open Data'. nous utilisons également des données venant de sites d'annonces, par exemple pour l'immobilier, ou d'instituts européens, enter autres pour ce qui est de la météo.

# Les notes
Nous utilisons une notation relative, car le but est de trouver la meilleure ville en France, et pas de juger si la meilleure est, en absolu, mauvaise, ou si la moins bonne est, en absolu, excellente. Nous voulons choisir une ville !

Pour chacune des catégories, nous attribuons donc une note sur 5. Les meilleures villes obtiennent 5, et les moins bonnes 1.

Pour calculer la note finale de la ville, et déterminer dans quelle catégorie elle se situe (1, 2, 3 ou "Podium", "Peloton" et "Poursuivants"), nous aggrégeons les notes de chaque catégorie en tenant compte de la pondération de chacune des catégories. En cas d'égalité, la ville avec la meilleure note sur le critère du loyer l'emporte. S'il y a encore une inégalité, la ville avec la meilleure connectivité internet gagne.

# La pondération
Nous adoptons une pondération très simple : dans une tradition [pastéquière](http://larevolutionpasteque.com/), nous considérons que "Cash is King", et nous donnons donc un coefficient 2 au Loyer. Toutes les autres catégories not un coefficient 1.

Cela nous permet de séparer les 250 plus grandes villes en 4 segments :
- Le podium (de la 1re à la 3ème ville)
- Le peloton (de la 4ème à 11ème ville)
- Les poursuivants (de la 12ème à 23ème ville)
- Les exclus, qui ne sont pas dans le classement (à partir de la 24ème ville)

# Questions, remarques, commentaires
- Votre ville ne figure pas au classement, et vous pensez qu'elle le devrait ? Envoyez-nous un email !
- Votre ville figure au classement, et vous pensez qu'elle ne le devrait pas ? Envoyez-nous un email ! 


