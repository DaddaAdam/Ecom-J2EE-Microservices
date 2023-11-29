# Ecom App Microservices

## Description

Ceci est le resultat de l'Activité Pratique 3 du cours de J2EE.

## Microservices (dans leur ordre de lancement)

- **Discovery Service** : Service de découverte des microservices
- **Gateway Service** : Service de routage et de redirection des requêtes
- **Config Service** : Service de configuration des microservices
- **Customer Service** : Service de gestion des clients
- **Inventory Service** : Service de gestion des produits
- **Billing Service** : Service de gestion des factures

## Eureka Discovery Service

- **URL** : http://localhost:8761

<img width="1680" alt="Screenshot 2023-11-29 at 11 59 03" src="https://github.com/DaddaAdam/Ecom-J2EE-Microservices/assets/77986052/16ac1e6e-fde2-499a-8cc4-bbd920f7d329">

## Liste des customers

- **GET** : http://localhost:8081/customers
  
<img width="1680" alt="Screenshot 2023-11-29 at 11 58 27" src="https://github.com/DaddaAdam/Ecom-J2EE-Microservices/assets/77986052/c2834cfd-c797-4aa1-b161-c0e1746e4eb5">

## Liste des customers via le Gateway Service

- **GET** : http://localhost:8888/customers
  
<img width="1680" alt="Screenshot 2023-11-29 at 11 58 44" src="https://github.com/DaddaAdam/Ecom-J2EE-Microservices/assets/77986052/f726ecd1-bc88-4b3c-8c35-03944c530c46">

## Liste des customers via le service name

- **GET** : http://localhost:8888/CUSTOMER-SERVICE/customers

<img width="1680" alt="Screenshot 2023-11-29 at 12 01 44" src="https://github.com/DaddaAdam/Ecom-J2EE-Microservices/assets/77986052/db8d891b-5402-441b-a825-85edc60a6586">

## Liste des produits

- **GET** : http://localhost:8082/products

<img width="1680" alt="Screenshot 2023-11-29 at 11 58 17" src="https://github.com/DaddaAdam/Ecom-J2EE-Microservices/assets/77986052/49d7784c-7f76-48d6-b29d-2ef659522232">

## Liste des produits via le Gateway Service

- **GET** : http://localhost:8888/products
  
<img width="1680" alt="Screenshot 2023-11-29 at 11 58 52" src="https://github.com/DaddaAdam/Ecom-J2EE-Microservices/assets/77986052/09a59d37-51b9-4700-9aeb-83f2cb0ca408">

## Liste des factures

- **GET** : http://localhost:8083/bills
  
<img width="1680" alt="Screenshot 2023-11-29 at 12 00 10" src="https://github.com/DaddaAdam/Ecom-J2EE-Microservices/assets/77986052/957c695c-65bb-44f9-96fd-ce625d2abf8b">

## Liste des factures via le Gateway Service

- **GET** : http://localhost:8888/bills
  
<img width="1680" alt="Screenshot 2023-11-29 at 12 00 10" src="https://github.com/DaddaAdam/Ecom-J2EE-Microservices/assets/77986052/c855cd9a-e399-4e04-9e20-6d5e12034cd9">

## Static + Dynamic Routing

- **Static Routing**

<img width="1680" alt="Screenshot 2023-11-29 at 12 13 07" src="https://github.com/DaddaAdam/Ecom-J2EE-Microservices/assets/77986052/9fa35d27-b9da-4b72-8c2d-05793db4b1e3">

- **Dynamic Routing**

<img width="1680" alt="Screenshot 2023-11-29 at 12 13 07" src="https://github.com/DaddaAdam/Ecom-J2EE-Microservices/assets/77986052/c4fbec92-20a2-4aba-9e83-3db3b616a916">
