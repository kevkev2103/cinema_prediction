# cinema_prediction

## Description

Ce projet vise à développer un outil de support décisionnel pour le cinéma "New is always better". L'outil utilise l'intelligence artificielle pour prédire la fréquentation des films lors de leur première semaine de projection. L'objectif est d'optimiser la programmation hebdomadaire des films et de maximiser les revenus du cinéma.

## Features

- Prédiction de la fréquentation des films basée sur des données historiques et des tendances actuelles.
- Interface web pour visualiser les prédictions et gérer la programmation des films.
- Automatisation du processus de collecte de données via scraping.
- Estimation du chiffre d'affaires et du bénéfice potentiel.

## Tech Stack

- **Python**: Pour le back-end et les scripts de machine learning.
- **Django**: Pour développer l'application web.
- **Scrapy**: Pour scraper les données nécessaires à l'entraînement du modèle.
- **FastAPI**: Pour exposer le modèle de machine learning via une API.
- **Docker**: Pour la conteneurisation et le déploiement.


## Installation

### Prérequis

- Docker
- Python 3.8+

### Lancer l'application

1. Clonez le dépôt :
  git@github.com:kevkev2103/cinema_prediction.git

Construisez les conteneurs Docker :
docker-compose up --build

Une fois l'application lancée, accédez à l'interface web via http://localhost:8000. Utilisez le tableau de bord pour :

    Voir les prédictions des films pour la semaine à venir.
    Consulter les données historiques et les performances des prédictions.
    Ajuster la programmation en fonction des prévisions de fréquentation.

    
