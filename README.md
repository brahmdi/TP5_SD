# TP5_SD
# Projet de Web Service pour la Conversion de Montant et la Gestion de Comptes

## Description

Ce projet a pour objectif de créer un Web service qui offre les fonctionnalités suivantes :
1. Conversion de montant de l'euro en dirham marocain (DH).
2. Consultation d'un compte.
3. Consultation d'une liste de comptes.

Le Web service est déployé avec un serveur JaxWS simple. Les opérations du Web service sont testées avec des outils tels que SoapUI ou Oxygen. Enfin, un client SOAP en Java est créé pour interagir avec le Web service.

## Étapes du Projet

### 1. Création du Web Service
![image](https://github.com/brahmdi/TP5_SD/assets/96790699/884c853b-9820-4eb5-871b-e44b0b22a263)


#### 1.1 Convertir un montant de l’euro en DH

Le Web service permet de convertir un montant donné en euros (EUR) en dirhams marocains (DH) en utilisant un taux de conversion fixe.
![image](https://github.com/brahmdi/TP5_SD/assets/96790699/7349590b-eff4-446f-8129-0b7204ba6ff7)


#### 1.2 Consulter un Compte

Le Web service offre la possibilité de consulter les détails d'un compte spécifique en fournissant l'identifiant du compte.
![image](https://github.com/brahmdi/TP5_SD/assets/96790699/b0b5cd75-2923-474f-b464-541ebd979bf5)


#### 1.3 Consulter une Liste de Comptes

![image](https://github.com/brahmdi/TP5_SD/assets/96790699/d1918954-9bf9-4023-896b-d6b9572c891c)


Le Web service permet de récupérer une liste de tous les comptes disponibles.

![image](https://github.com/brahmdi/TP5_SD/assets/96790699/2b2c3072-3f54-49a5-93ed-090f9915b8a8)


### 2. Déploiement du Web Service avec un Serveur JaxWS

Le Web service est déployé sur un serveur JaxWS simple, qui permet de l'exposer pour des requêtes HTTP.
![image](https://github.com/brahmdi/TP5_SD/assets/96790699/da05c966-1845-4b69-9d84-ec716b65f58a)


### 3. Consultation et Analyse du WSDL

Le fichier WSDL (Web Services Description Language) du Web service peut être consulté et analysé via un navigateur HTTP pour comprendre les opérations disponibles et leurs schémas de requête/réponse.

![image](https://github.com/brahmdi/TP5_SD/assets/96790699/1fea1142-446c-4ed6-bc70-bf6ae7209cb3)


### 4. Test des Opérations du Web Service

Les opérations du Web service sont testées à l'aide d'outils tels que SoapUI ou Oxygen pour garantir leur bon fonctionnement et valider les réponses attendues.

### 5. Création d'un Client SOAP Java
![image](https://github.com/brahmdi/TP5_SD/assets/96790699/a475bbf9-a1a7-4746-8529-2d7e6028c49e)

# tester methode de conversion en euro : 

![image](https://github.com/brahmdi/TP5_SD/assets/96790699/f72db637-14a9-4f08-b4d8-60a4f6580196)


#### 5.1 Génération du Stub à partir du WSDL

Un stub Java est généré à partir du fichier WSDL du Web service pour faciliter l'interaction avec le service.

#### 5.2 Création d'un Client SOAP

Un client SOAP en Java est créé pour envoyer des requêtes au Web service et traiter les réponses.

![image](https://github.com/brahmdi/TP5_SD/assets/96790699/98815d3d-c70d-42a6-920b-36ce38f30ee3)


## Prérequis

- Java Development Kit (JDK)
- Apache Maven
- Serveur JaxWS
- SoapUI ou Oxygen pour les tests
