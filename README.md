# Projet_Python_GB4

## Auteurs : 

Maëna Degoul, Sarah Ung, Angélique Vella 
Etudiante en 4ème année de Génie Biologique à Polytech Nice Sophia - 2023/2024

## Objectif du programme

Ce projet a pour but l'analyse d’une structure protéique au format PDB soit par l’ouverture d’un fichier soit par la récupération des données via le site web de la PDB. Différentes analyses seront effectuées sur ces données et seront stockées dans des fichiers de résultats.

Nous vous proposons donc une interface utilisable par tous qui génère une visualisation des différentes analyses et permet de récupérer l’ensemble de ces résultats dans un fichier. Nous sommes convaincus que ces efforts contribueront à une meilleure compréhension de la complexité moléculaire et faciliteront la conception de nouvelles stratégies thérapeutiques.

## Etapes d'installation 

1. Installer la version Python 3 (3.11 idéalement ou au-delà) en cliquant sur ce lien: [https://www.python.org/downloads/release/python-3115/](https://colab.research.google.com/corgiredirector?site=https%3A%2F%2Fwww.python.org%2Fdownloads%2Frelease%2Fpython-3115%2F) . Veuillez sélectionner la la case "Ajouter Python aux variable de chemin" (PATH) lors de l'installation pour le bon fonctionnement du programme.

2. Installer la liste des modules complémentaires nécessaires à l'exécution des fonctions en les tapant dans le terminal de commande. Elles sont listées dans le fichier "Import".
Attention, ces commandes nécessitent une installation préalable de pip.

3. Exécuter le fichier "Script" pour visualiser l'interface

## Utilisation 

1. Le logiciel permet de charger en ligne ou en local une fiche PDB (exemple: 1CRN.pdb)

2. Le logiciel a besoin d'une connexion internet pour fonctionner, particulièrement pour le chargement en ligne.

3. Le chargement d'un fichier en ligne se réalise en inscrivant l'identifiant de la molécule sans l'extention ".pdb"

4. Si vous voulez ouvrir une fiche en local, veuillez respecter la nomenclature du fichier : nom_fichier = identifiant_molecule.pdb 

5. L'interface est composée de 2 applications dépendantes : l'une d'initialisation qui permet le chargement du fichier, et l'autre de gestion qui permet la visualisation des données. Des paragraphes d'explication sont prévus dans chaque fenêtre pour indiquer le contenu des données visualisées ainsi que les actions réalisables sur cette fenêtre.

6. Veillez à fermer la fenêtre ouverte pour terminer le programme.