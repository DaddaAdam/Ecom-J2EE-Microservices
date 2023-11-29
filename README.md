# Ecom App Microservices

## Description

Ceci est le resultat de l'Activité Pratique 2 du cours de J2EE.

## Microservices (dans leur ordre de lancement)

- **Discovery Service** : Service de découverte des microservices
- **Gateway Service** : Service de routage et de redirection des requêtes
- **Config Service** : Service de configuration des microservices
- **Customer Service** : Service de gestion des clients
- **Inventory Service** : Service de gestion des produits
- **Billing Service** : Service de gestion des factures

## Eureka Discovery Service

- **URL** : http://localhost:8761

## Liste des customers

- **GET** : http://localhost:8081/customers

## Liste des customers via le Gateway Service

- **GET** : http://localhost:8888/customers

## Liste des customers via le service name

- **GET** : http://localhost:8888/CUSTOMER-SERVICE/customers

## Liste des produits

- **GET** : http://localhost:8082/products

## Liste des produits via le Gateway Service

- **GET** : http://localhost:8888/products

## Liste des factures

- **GET** : http://localhost:8083/bills

## Liste des factures via le Gateway Service

- **GET** : http://localhost:8888/bills

## Static + Dynamic Routing


