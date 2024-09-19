# Facturations - Application de Gestion de Clients

## Description
**Facturations** est une application de gestion de clients permettant aux utilisateurs de gérer les informations clients et de suivre les facturations associées. Ce projet est développé en **Java 17** avec **Spring Boot** et utilise une base de données **MySQL** pour stocker les données.

L'application suit les principes de l'architecture RESTful et utilise le framework Spring pour faciliter le développement des services et des APIs. La gestion des factures permet de créer, modifier, consulter et supprimer des factures associées aux clients enregistrés dans le système.

## Fonctionnalités
- Gestion des clients (ajout, mise à jour, suppression, visualisation)
- Gestion des factures pour chaque client
- API REST pour la gestion des factures et des clients
- Utilisation de **Spring Boot** pour le backend
- Persistance des données avec **MySQL**
- Sécurisation des endpoints avec JWT (si applicable)
- Documentation de l'API avec **Swagger** (si applicable)

## Technologies utilisées
- **Java 17**
- **Spring Boot 2.x**
- **Spring Data JPA**
- **Spring Security** (optionnel pour l'authentification et l'autorisation)
- **MySQL** (SGBD relationnel)
- **Maven** (gestionnaire de dépendances)



## Prérequis
- **Java 17** ou supérieur
- **Maven 3.x**
- **MySQL** installé et configuré
- **Docker** (optionnel pour déploiement conteneurisé)

## Installation et Configuration

1. **Cloner le dépôt :**
    ```bash
    git clone https://github.com/votre-utilisateur/facturations.git
    cd facturations
    ```

2. **Configurer la base de données :**
   Créez une base de données MySQL pour l'application :
   ```sql
   CREATE DATABASE facturations_db;
