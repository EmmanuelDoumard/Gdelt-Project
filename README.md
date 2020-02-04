![Gdelt](https://github.com/Korbenik/Gdelt-Project/blob/master/main.jpg)

# GDELT 2019

## Analyse de l'année 2019 via la base de données GDELT 

L’objectif du projet est de concevoir un système qui permet d’analyser le jeu de donnees GDELT et ses sources de données.Il permettra de voir l’évolution des relations entre les différents pays, en étudiant le ton des mentions (positives/negatives) dans les articles médias de chaque pays.

Notre groupe de travail est composé de : Emmanuel DOUMARD, Hicham EL OUATIKI, Paul LEGOUX, Jean-Galbert ONGONO OLINGA, Ialifinaritra RAKOTONIAINA


## Architecture proposée 

![Architecture](https://github.com/Korbenik/Gdelt-Project/blob/master/architecture.PNG)


## Chargement des zip dans le bucket S3 

Les fichiers GDELT events et GDELT Gkg de l'année 2019 ont été chargés sur le bucket S3 à partir du script suivant : 

[Chargement des données dans S3]


## Extraction et preprocessing des données 

Nous avons extrait les features utiles des données pour répondre aux requetes.

[Preprocessing]


## Création des tables Cassandra

[Script création table Cassandra]


## Visualisation 

Les requetes ont été effectués sur Cassandra et visualisés grâce à l'outil de visualisation Zeppelin 

[Requete Cassandra et Visualisation]

## Présentation du projet 

[Présentation]


