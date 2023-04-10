# MusicID

## Description

L'approche sémantique se réfère à l'analyse du sens des mots et des phrases dans un texte donné. Elle s'intéresse à la fois à la signification littérale des mots et à leur signification contextuelle, en se concentrant sur la façon dont les mots et les phrases sont utilisés dans différentes situations de communication. Elle est utilisée dans différents domaines, notamment en linguistique, en psychologie cognitive, en intelligence artificielle ou encore en traitement automatique du langage naturel.

MusicID a pour but de donner une nouvelle identité à chaque musique en extrayant ses thèmes et en les associant à chaque artiste afin de pouvoir créer des nouvelles liaisons entre chaque artiste. Nos utilisateurs ciblés sont des plateformes de streaming tel que Spotify, Deezer ou Apple Music qui pourront faire découvrir à leurs utilisateurs des chansons et des auteurs regroupés dans des nouveaux thèmes encore jamais pensé. Notre projet pourra donner de la  visibilité aux artistes moins connus en les regroupant dans les thèmes qu’ils ont en commun avec des artistes plus populaires tout en permettant aux artistes eux-mêmes de mieux comprendre les thèmes dans lesquels leurs musiques peuvent être classées.

## Membres

### WP0: Gestion
- Anne-Sophia LIM
- François SOULIÉ
- Paul TISSEDRE
- Clément THIVEYRAT

### WP1: Data
- Johan KHA
- Yanis PERRIN
- Antoine SUSINI
- Kalisto WILLAEY

### WP2: Ontologie
- Tristan PAILLET
- Quentin PORRY
- Morgane RAYMOND

### WP3: Graphes
- Lucas MEDINA
- Amaël MUZEAU
- Trang Anh NGUYEN
- Guilherme PEREIRA

## Gestion

### Description de la tâche

Le rôle du groupe de gestion a été de faciliter la communication de manière globale au sein du projet entre chaque groupe, la faciliter en mettant plusieurs outils à disposition (discord, github,...) et vérifier, de par une méthode agile, au bon avancement du projet. Bien entendu, notre groupe a aussi essayé de se mettre à la disposition des autres groupes en cas de problèmes afin de veiller à ce que chaque groupe ne se retrouve pas bloqué. 

### Outils utilisés

- <img src="https://japaniste.fr/wp-content/uploads/2019/12/discord-logo-logodownload-download-logotipos-1.png" width="20" height="20"> Discord 
- <img src="https://i.imgur.com/3KuWqKX.jpg" width="20" height="20"> Github
- <img src="https://i.imgur.com/z9csoYY.png" width="20" height="20"> Trello
- <img src="https://i.imgur.com/uJpua3V.png" width="20" height="20"> Google Drive


### Problèmes rencontrés

1. Il est peu commun dans notre cursus scolaire d’avoir un projet avec autant de participants (15 personnes). Le rôle de coordinateur est donc important et il peut être difficile de garder un œil sur tout ce qu’il se passe. Pour répondre à ce problème nous avons organisé des réunions bihebdomadaires afin de faciliter la communication en plus de permettre à chacun d’avoir une idée de l’avancement des autres groupes. 

2. Le projet étant étalé sur plusieurs semaines et n’ayant qu’une séance par semaine, il peut être difficile de garder un rythme et une motivation cohérente à l’intérieur des différents groupes. Pour pallier ce problème nous avons en dehors des réunions pris la liberté d’avoir des discussions informelles sur la tournure générale du projet. De tels échanges permettent non seulement de garder le sujet en tête mais également de progresser dans la ligne directrice du projet.  

## Data

### Description de la tâche

### Outils utilisés

### Problèmes rencontrés








## Ontologie

### Description de la tâche

Le groupe WP2 avait pour mission de réaliser l’ontologie de notre projet à l’aide de renseignements provenant du cours et de diverses recherches complémentaires sur internet. L’utilisation de DBpedia ne correspondant pas au projet, notre groupe s'est orienté vers l’utilisation de l’application protégé avec laquelle notre ontologie a évolué au fil des séances, jusqu’à aboutir à notre ontologie actuelle.

### Outils utilisés

- <img src="https://i.imgur.com/ScPGXjg.png" width="20" height="20"> DBpedia
- <img src="https://i.imgur.com/MVFCXVt.gif" width="20" height="20"> Protégé



### Problèmes rencontrés

1. Nous avons initialement essayé d’utiliser DBpedia, mais malheureusement nous n’avons pas réussi à aboutir à un résultat satisfaisant pour notre projet.

2. Nous n’avions jamais vraiment eu de cours sur les ontologies avant celui-ci et encore moins de cours sur l’utilisation de Protégé, deuxième logiciel utilisé. La compréhension de cet outil a donc nécessité un investissement temporel non négligeable. En effet, notre objectif était de fournir un travail de qualité, et un tel objectif passe par une phase de recherches et d’approfondissement qui est forcément temporellement coûteuse mais nécessaire. 

3. Les ontologies étant un nouveau monde à explorer il a été ardu de fabriquer notre ontologie et cela en gardant bien les objectifs du projet en tête. Afin de ne pas se perdre nous restions en contact avec les autres membres du projet afin de nous permettre de synchroniser nos ambitions et nos objectifs.


## Graphe

### Description de la tâche

La mission du groupe graphe était originellement, à l’aide de l’ontologie, de réaliser des graphes en utilisant Neo4j. Cependant, comme nous avons travaillé  dès le début de l’unité, le groupe graphe c’est entraîné à l’aide d’un csv de test afin d’obtenir le plus tôt possible un algorithme (gSpand) opérationnel qui permettra ensuite d’interpréter les résultats extrait à partir de l’ontologie.

### Outils utilisés

- <img src="https://i.imgur.com/3KuWqKX.jpg" width="20" height="20">Neo4j
- <img src="https://i.imgur.com/mEJN8v6.png" width="20" height="20">Python

### Problèmes rencontrés

1. Nous avons eu du mal à appréhender les commande interne à neo4j pour l'import de l'ontologie car elles n’existaient pas dans neo4j de base et nous avons donc eu du mal à les implémenter par la suite.

2. Nous avons aussi rencontré un problème de format lors de l’import des données depuis notre csv.


