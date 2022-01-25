# Dedoublenage-des-valeurs-immobilieres

L'approche consiste dans un 1er temps à faire un clustering des biens immobiliers en utilisant uniquement les textes contenus dans la colonne "DESCRIPTION" du dataframe. Ensuite, pour chaque cluster obtenu précédemment, on effectue un micro-cluster en utilisant uniquement certaines colonnes (feature engineering)  pertinentes autres que la colonne "DESCRIPTION".

J'ai obtenu les résultats suivants :

* Nombre de biens immobiliers sans doublons :  959

* Nombre de biens immobiliers avec doublons :  357

Restitution des résultats :

J'ai généré un fichier zip qui contient un ensemble de fichiers utiles à l'interprétation des résultats algorithmiques.

Le lien vers le zip est : https://drive.google.com/file/d/1Ng2WbagNHM1y2vE8y9fCztCfLqKW-37k/view?usp=sharing

Description des fichiers joints dans le zip :

* "doublons.csv" : Il contient les biens immobiliers présents en doublons. Un ensemble de biens en doublons est séparé des autres par une ligne vide dans le fichier csv

* "sans_doublons.csv" : Il contient les biens immobiliers qui ne sont pas en doublons

* "Yanport_test_technique_data_scientist_alternance.ipynb" : notebook python
