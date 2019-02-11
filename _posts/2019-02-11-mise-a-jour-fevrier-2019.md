---
layout: post
title:  Mise à jour Février 2019
excerpt_separator: <!--more-->
date: "2019-02-11 00:00:00"
description: Mise à jour standard... Et complaintes sur le régime des associations en alsace.
lang: fr
locale: fr_FR
author: Hector
---

# Mise à jour Février 2019

Comme tous les mois, la mise à jour de Février amène quelques changements à la méthodologie du classement et aux données de base ! 

<!--more-->

## Mise à jour des loyers

Le premier changement est l'habituelle mise à jour des prix des loyers, grâces aux données récoltées pendant le mois précédent. Cette mise à jour de nos données n'a pas fait bouger le classement d'un poil, signe que nos données commencent à être de plus en plus fiables.

Il faudra peut-être commencer à ne prendre en considération que le prix des loyers sur les 6 derniers mois, afin de renforcer la fiabilité de la donnée, et permettre au classement de s'adapter aux conditions réelles. Mais réservons ce changement pour de prochains mois, voire pour la fin de l'année 2019... Il se pourrait en effet que mes scrappers n'indiquent pas la date de publication des annonces immobilières, et ne mentionnent pas non plus dans le format de sortie la date à laquelle la donnée a été identifiée... A suivre !

## Prix des courses en supermarché

Un peu par accident, je suis tombé sur une magnifique carte de France montrant le prix moyen des courses que nous réalisons chaque mois, département par département. Les chiffres vont de 350€ à 415€ : au final, c'est assez rapproché, mais il y a tout de même une différence, qui se fait bien sentir. Bien sûr, ces chiffres dépendent beaucoup de l'enseigne et de la localisation précise de cette dernière, mais globalement, ces prix nous donnent une bonne indication du coût de la vie.

J'ai donc ajouté ce critère au Loyer. Cela m'a permis par la même occasion de simplifier significativement la méthode de calcul de la note de loyer : elle correspond maintenant aux quintiles, alors qu'auparavant j'utilisais un calcul plus complexe.

## Un nouveau critère ?

Troisième mise à jour importante.... Une tentative avortée. Voilà, c'est dit. Je suis toujours à l'affut de nouveaux critères pour affiner mon classement, mais je suis très pointilleux. Si vous me proposez un critère, je vais m'assurer qu'il respecte plusieurs caractéristiques :
* Il doit être univoque, c'est à dire qu'il est clair qu'il est indiscutable que lorsque la note est élevée, c'est un point positif, et que quand la note est faible, c'est un point négatif. Ce n'est pas toujours évident. Par exemple, j'ai hésité à intégrer le nombre de policiers dans la note de sécurité. Mais un nombre de policier élevé est-il un signe d'une sécurité accrue, ou d'une délinquance particulièrement élevée ? Ce n'est pas évident, et un nombre de policier élevé peut probablement indiquer chacun de ces deux cas.
* Il doit être disponnible en ligne, sans trop de soucis. Dans l'idéal, sous la forme d'une base de donnée, ou structurée d'une autre manière, sur un site internet que je peux scraper avec mes petits programmes en python. Au pire, si la donnée est très intéressante, je peux aussi passer une petite heure à la noter pour les 250 villes que j'ai dans mon classement initial.
* Il doit être disponible sur la totalité du territoire, pour des raisons évidentes : si je ne peux pas noter certaines villes, comment peut-on avoir un classement objectif au niveau national ?

Je suis assez exigeant sur ces caractéristiques, parce qu'à chaque donnée ou chaque critère que j'ajoute, la complexité du classement s'accroit. Et le gain est généralement marginal, il me faut donc être vigilant pour ne pas aboutir à un classement incompréhensible, plein de particularités et difficile à comprendre dans son ensemble. 

C'est la suggestion d'un admirateur Niçois qui m'a plût - "admirateur" est peut-être un mot un peu fort, mais il n'y a pas de commentaires sur ce blog, personne ne pourra se plaindre ! Cette suggestion, c'est d'intégrer le nombre d'associations dans l'animation. C'est une excellente idée ! Les associations peuvent être sportives, culturelles, associatives... Elles sont clairement un reflet de l'implication des citoyens dans la vie de leur communauté. 

Je me léchais les babines. J'avais hâte. Je cours sur internet, je trouve le RNA, le Registre National des Associations, qui propose deux fichiers en ligne, contenant l'ensemble des associations françaises. J'intègre la donnée à mon classement. Tout se passe bien.... Puis je remarque une erreur bizare sur quelques villes. En particulier, sur Mulhouse et Strasbourg.

Boudiou ! Encore la faute à ces andouilles de teutons. L'alsace et la moselle étaient Allemandes lors de l'entrée en vigueur de la loi sur les associations de 1901. Déception, pleurs, tristesse. Et voilà comment l'héritage historique de l'Est français a pourri mon week-end.

Je n'en reste pas moins déterminé à améliorer chacune des notes que j'attribue à nos villes françaises. Si vous avez des idées, n'hésitez pas à m'en faire part ! Et si possible, vérifiez d'abord que la donnée est disponible en Alsace Moselle, merci !