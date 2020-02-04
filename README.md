![Gdelt](https://github.com/Korbenik/Gdelt-Project/blob/master/main.jpg)

# GDELT 2019

## Analyse de l'année 2019 via la base de données GDELT 

L’objectif du projet est de concevoir un système qui permet d’analyser le jeu de donnees GDELT et ses sources de données.Il permettra de voir l’évolution des relations entre les différents pays, en étudiant le ton des mentions (positives/negatives) dans les articles médias de chaque pays.

Notre groupe de travail est composé de : Emmanuel DOUMARD, Hicham EL OUATIKI, Paul LEGOUX, Jean-Galbert ONGONO OLINGA, Ialifinaritra RAKOTONIAINA


## Architecture proposée 

![Architecture](https://github.com/Korbenik/Gdelt-Project/blob/master/architecture%20.PNG)


## Chargement des zip dans le bucket S3 

Les fichiers GDELT events et GDELT Gkg de l'année 2019 ont été chargés sur le bucket S3 à partir du script suivant : 

[Chargement des données dans S3](https://github.com/Korbenik/Gdelt-Project/blob/master/Data_importation_to_S3.json)


## Extraction et preprocessing des données 

Nous avons extrait les features utiles des données pour répondre aux requetes.

[Preprocessing](https://github.com/Korbenik/Gdelt-Project/blob/master/Bucket_to_Cassandra.json)


## Création des tables Cassandra

[Script création table Cassandra](https://github.com/Korbenik/Gdelt-Project/blob/master/cassandra_script.sh)


## Visualisation 

Les requetes ont été effectués sur Cassandra et visualisés grâce à l'outil de visualisation Zeppelin 

[Requete Cassandra et Visualisation](https://github.com/Korbenik/Gdelt-Project/blob/master/Visualisation.json)

## Présentation du projet 

[Présentation finale](https://github.com/Korbenik/Gdelt-Project/blob/master/Projet%20Big%20Data%202019_%20GDELT.pdf)


