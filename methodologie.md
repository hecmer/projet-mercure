---
layout: methodologie
---
# Introduction

L'objectif final de ce classement est de permettre à des travailleurs nomades de s'implanter (à court ou long terme) dans des lieux adaptés à leurs besoins, en France. Nomadist & co font déjà un très bon travail pour couvrir les villes internationales, mais nous restons confrontés à une problématique : pour être résident fiscal français, et donc ne pas avoir d'ennuis ou de complications fiscales, il nous faut résider pendant environ 6 mois par ans en France. Dés lors, où devons-nous nous établir ?

Projet Mercure utilise des sources ouvertes afin d'alimenter un algorythme qui note chacune des charactéristiques des villes, et permet ainsi d'obtenir un classement cohérent et objectif.

# Les Sources
Nous utilisons uniquement des sources ouvertes. Les informations sont récupérées grâce à des scrapers, et sont aggrégées par un algorythme. Très franchement, nous sommes tentés de parler d'IA. C'est super intelligent de collecter de l'information d'un nombre de sources limitées, et de les aggréger toujours de la même manière, non ? C'est même du Machine Learning, que dis-je du Deep Learning ! ON se sert même d'une Blockch... Sorry j'en peux plus il est trois heures du mat.

DONC, les sources. Ce sont les suivantes, sortez vos callepins :

| Catégorie     | Source                 | Commentaires                                                   |
| ------------- | ---------------------- | -------------------------------------------------------------- |
| Loyer         | Agences immobilières   | On scrape, on scrape, à droite à gauche. On a >10k d'annonces  |
| Animation     | Guides touristiques    | On compte le nombre de resto par habitants (nb resto/nb hab)   |
| Sécurité      | INSEE - délinquance    | On interprète les données de délinquance de l'INSEE & GOUV     |
| Internet      | ARCEP                  | C'est une combinaison des données internet fixe et 4G          |
| Météo         | Météo France           | Surprise ! Météo France a des données sur la météo !           |
| Transports    | SNCF & Wikipedia       | Nous prenons en considération les aéroports et gares TGV       |
| Coworkings    | Annuaires de coworking | On ne fait que des choses légales. On cherche des coworkings.  |

Vous remarquerez, si vous êtes attentifs, que les informations dans le tableau ci-dessus ne sont pas *très* explicites... C'est volontaire, et lié à deux raisons :
- On ne veut pas donner le nom de nos meilleurs ingrédients
- On ne veut pas donner la recette complète de notre sauce secrète

Eh oui ! Nous avons envie d'être transparent, pour que vous puissiez comprendre ce que vous regardez, mais nous ne voulons pas non plus tout offrir sur un plateau !

# Les notes
Nous utilisons une notation relative, car le but est de trouver la meilleure ville en France, et pas de juger si la meilleure est, en absolu, mauvaise, ou si la moins bonne est, en absolu, excellente. Nous voulons choisir une ville ! 

Pour chacune des catégories, nous attribuons une note sur 5. Les meilleures villes obtiennent 5, et les moins bonnes 1.

Pour calculer la note finale de l'entreprise, et déterminer dans quelle catégorie elle se situe (1, 2, 3 ou "Podium", "Peloton" et "Poursuivants"), nous aggrégeons les notes de chaque catégorie en tenant compte de la pondération de chacune des catégories.

# La pondération
Nous adoptons une pondération très simple : dans une tradition pastéquière, nous considérons que "Cash is King", et nous donnons donc un coefficient 2 au Loyer. Toutes les autres catégories not un coefficient 1.

Cela nous permet de séparer les 250 plus grandes villes en 4 segments :
- Le podium (classements 1 à 3)
- Le peloton (classements 4 à 11)
- Les poursuivants (classements 12 à 23)
- Les exclus, qui ne sont pas dans le classement (classements 24 à 250)

# Questions, remarques, commentaires
- Votre ville ne figure pas au classement, et vous pensez qu'elle le devrait ? Envoyez-nous un email !
- Votre ville figure au classement, et vous pensez qu'elle ne le devrait pas ? Envoyez-nous un email ! 


