# Analyse du risque des feux de foret
Projet de Statistiques Appliquées effectué de novembre 2023 à mai 2024
 **Encadrants** : Antoine Heranval, Thomas Peyrat
 **Etudiants** : Olivier Pinatel, Margaux Duperier, Juliette Schneider
 **Référent pédagogique** : Olivier Lopez

Ce projet s'appuie principalement sur la Base de Données sur les Incendies de Forêts en France (BDIFF) et sur la base de données des IFM de 2006 à 2100 pour la région des Landes provenant du DRIAS.
Il a pour but de prédire à partir des IFM la survenance de feux de forêts dans les Landes durant la période estivale pour les années 2024 à 2100.

Le premier dossier **"Manipulations préliminaires - BDIFF"** est constitué de statistiques descriptives et de représentations graphiques des données de la base BDIFF (recensant les incendies de forêts en France par communes de 2006 à 2022).

Le deuxième dossier **"Modèles de prédictions des feux par les IFM"** est constituté des codes suivant :
- *base_ifm_communes* : mise en forme de nos données afin de construire nos tableaux X et Y qui serviront ensuite à appliquer nos modèles de prédiction
- *Modèles* : application de différents modèles à nos tableaux X et Y afin de choisir le plus adapté pour nos prédictions
- *Prédictions* : application du modèle choisit à notre Y_projection_2100, la base des IFM moyen par maille de 2023 à 2100, afin d'obtenir notre X_prédit, vecteur ou à chaque maille on donne la probabilité de la survenance d'au moins un feu durant la période estivale, et représentations graphiques des résultats
