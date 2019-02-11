---
layout: methodologie
lang: en
---

# Introduction

The ultimate goal of this ranking is to allow nomad or remote workers to set up in best place in France. Nomadlist & many others make a great job at covering international cities, but struggle when in comes to secondary cities or national importance, but with limited international exposure.

Remote France uses open source data in order to feed an algorythm which rates each of the cities according to a series of criteria. This allows us to obtain a consistent and objective ranking.

# Description of the ratings
## Rent
The rent is a very important criteria. We compute the median monthly rent for an appartment or house with one bedroom, and one to two rooms. We also incorporate in this rating the cost of groceries. The general idea is to know how much it would cost to live alone or in a couple in each of the french cities.

## Life
A lively city is a city where is it good to spend time, where one can go out and make new acquaintances. The Life rating gives us a general idea of this. It is based on the number of bars and restaurants per inhabitants, and on the proportion of students in the city. To be noted, the proportion of students can be above 100%, in the cases where many students are attending a university of the city, but live in the peripheric cities.

## Safety
The rent criteria is great, but it has limits. The safety criteria aims at correcting one of those limits. Indeed, rents tend to be very low is unsafe areas, where criminality rates are very high. We aim at controlling this shortcoming with the Safety rating, which allows us to highlight safe cities.

## Internet
We use two metrics to compute the Internet rating:
* The quality of the mobile network and 4G coverage
* The quality of the fixed internet (speed of ADSL & optic fiber connections)

These two metrics allow us to ensure that the city we will end up choosing has a sufficient infrastructure to allow us to work, watch movies and play video games without troubles.

## Weather
A hot and sunny weather is more confortable than a cold and rainy weather. Sure, it depends on personal taste, but that's the consensus, and we followed along. This criteria aggregates both the annual precipitations, and the average temperature of each of the cities.

We also add a bonus to the cities that are located in the mountains, or on the seaside. These environment typically make it easier to tolerate the weather. Who would complain of a cold weather in the mountains? (Ski, yeah!)

## Transports
Being able to move around easily is a very important criteria. If you're not able to go to your city easily, working can be more difficult. If transportation is not a criteria for you, you may want to consider setting yourself up in the back country in a nice farm, and enjoy the solitude. 

But for our purpose, we favor cities that are well integrated into the national railroad system, and that have an airport.

## Coworkings
Working home is not for everyone. Having an office or a place to work can significantly boost your productivity, and that's what coworkings are for. The coworking rating only takes into account the number of coworkings, in proportion of the size of the city, and not the prices of these coworkings. 

The prices are actually quite predictable : 175€-250€ per month for a fixed desk & 24/7 access. Add about a 100€ to get the prices in Paris (which will obviously be in the upper part of your updated range)

# Sources
We only use open sources. The information are retrieved thanks to scrapers, and are aggregated by our algorythm. Frankly, we are very tempted to call this an AI. Isn't it very *intelligent* to collect data from a finite number of sources and to systematically aggregate them? It might even be Machine learning - wait, it's deep learning! We could even use a Blockcha.... sorry, I can't take it anymore it's 3am.

More seriously, our sources are mainly data provided by the french government through its "Open Data" initiatives, of which we are **very** fond. We also use additional data from european institutions and other organizations.

# The ranking
For each of the rating categories, we attribute a rating from 1 to 5. The smaller the grade, the worse it is. 

To compute the final rating of a city, and determine in which of our 3 layers it will end up on our main page, we sum all the ratings, raking into account the weights described below. if there is a tie, the city with the best Rent rating wins. If there is still a tie, the city with the best internet rating wins. If there is *still* a tie, the city with the best transports rating wins. That about covers it all!

# Weights
We have a very simple weighting policy: all ratings have a weight 1, except for the rent, which has a weight of 2. The reason for this is that we consider that "Cash is King", and that the rent is a paramount criteria to choose where to settle up.

# Questions, remarks, comments?
- A city you like is not in our ranking, and you think it should be? Shoot us an email!
- Your city is in the ranking, but you think it shouldn't be? SHoot us an email!