# Gestionnaire de Projets Fullstack (MERN)

# Statut
En cours

# Vue d'ensemble
Le Gestionnaire de Projets Basé sur le Cloud est une application web conçue pour simplifier la gestion des projets d'équipe. Construit en utilisant la pile MERN (MongoDB, Express.js, React et Node.js), cette plateforme offre une interface utilisateur conviviale pour une gestion efficace des projets, l'assignation des tâches, le suivi et la collaboration. L'application est destinée aux administrateurs et aux utilisateurs réguliers, offrant des fonctionnalités complètes pour améliorer la productivité et l'organisation.

### Pourquoi/Problème ?
Dans un environnement de travail dynamique, une gestion de projet efficace est cruciale pour le succès de l'équipe. Les méthodes traditionnelles de suivi des tâches via des tableurs ou des systèmes manuels peuvent être lourdes et sujettes à des erreurs. Le Gestionnaire de Projets Basé sur le Cloud vise à relever ces défis en fournissant une plateforme centralisée pour la gestion des tâches, permettant une collaboration transparente et une meilleure efficacité du flux de travail.

### **Contexte** :
Avec l'essor du travail à distance et des équipes dispersées, il existe un besoin croissant d'outils facilitant une communication efficace et la coordination des projets. Le Gestionnaire de Projets Basé sur le Cloud répond à ce besoin en tirant parti des technologies web modernes pour créer une solution de gestion de tâches intuitive et réactive. La pile MERN assure l'évolutivité, tandis que l'intégration de Redux Toolkit, Headless UI et Tailwind CSS améliore l'expérience utilisateur et les performances.

### 
## **Fonctionnalités Administrateur :**
1. **Gestion des Utilisateurs :**
    - Créer des comptes administrateurs.
    - Ajouter et gérer les membres de l'équipe.

2. **Attribution des Tâches :**
    - Assigner des tâches à un ou plusieurs utilisateurs.
    - Mettre à jour les détails et le statut des tâches.

3. **Propriétés des Tâches :**
    - Marquer les tâches comme à faire, en cours ou terminées.
    - Assigner des niveaux de priorité (élevé, moyen, normal, faible).
    - Ajouter et gérer des sous-tâches.

4. **Gestion des Actifs :**
    - Télécharger des actifs de projet, tels que des images.

5. **Contrôle des Comptes Utilisateurs :**
    - Désactiver ou activer les comptes utilisateurs.
    - Supprimer définitivement ou mettre à la poubelle les tâches.

## **Fonctionnalités Utilisateur :**
1. **Interaction avec les Tâches :**
    - Changer le statut des tâches (en cours ou terminées).
    - Voir les informations détaillées des tâches.

2. **Communication :**
    - Ajouter des commentaires ou discuter des activités liées aux tâches.

## **Fonctionnalités Générales :**
1. **Authentification et Autorisation :**
    - Connexion utilisateur avec authentification sécurisée.
    - Contrôle d'accès basé sur les rôles.

2. **Gestion du Profil :**
    - Mettre à jour les profils utilisateurs.

3. **Gestion des Mots de Passe :**
    - Changer les mots de passe de manière sécurisée.

4. **Tableau de Bord :**
    - Fournir un résumé des activités de l'utilisateur.
    - Filtrer les tâches en à faire, en cours ou terminées.

## **Technologies Utilisées :**
- **Frontend :**
    - React (Vite)
    - Redux Toolkit pour la gestion de l'état
    - Headless UI
    - Tailwind CSS

- **Backend :**
    - Node.js avec Express.js
    
- **Base de données :**
    - MongoDB pour un stockage des données efficace et évolutif.

Le Gestionnaire de Projets Basé sur le Cloud est une solution innovante qui apporte efficacité et organisation à la gestion des tâches au sein des équipes. En exploitant la puissance de la pile MERN et des technologies frontend modernes, la plateforme offre une expérience transparente tant pour les administrateurs que pour les utilisateurs, favorisant la collaboration et la productivité.

&nbsp;

## INSTRUCTIONS DE CONFIGURATION

# Configuration du Serveur

## Variables d'environnement
D'abord, créez le fichier de variables d'environnement `.env` dans le dossier du serveur. Le fichier `.env` contient les variables d'environnement suivantes :

- MONGODB_URI = `votre URL MongoDB`
- JWT_SECRET = `une clé secrète - doit être sécurisée`
- PORT = `8800` ou tout autre numéro de port
- NODE_ENV = `développement`

&nbsp;

## Configuration de MongoDB :

1. La configuration de MongoDB implique plusieurs étapes :
    - Visitez le site web de MongoDB Atlas
        - Rendez-vous sur le site web de MongoDB Atlas : [https://www.mongodb.com/cloud/atlas](https://www.mongodb.com/cloud/atlas).

    - Créez un compte
    - Connectez-vous à votre compte MongoDB Atlas.
    - Créez un nouveau cluster
    - Choisissez un fournisseur de cloud et une région
    - Configurez les paramètres du cluster
    - Créez le cluster
    - Attendez que le cluster soit déployé
    - Créez un utilisateur de base de données
    - Configurez la liste blanche des IP
    - Connectez-vous au cluster
    - Configurez votre application
    - Testez la connexion

2. Créez une nouvelle base de données et configurez le fichier `.env` avec l'URL de connexion MongoDB.

## Étapes pour lancer le serveur

1. Ouvrez le projet dans l'éditeur de votre choix.
2. Naviguez dans le répertoire du serveur `cd server`.
3. Exécutez `npm i` ou `npm install` pour installer les paquets.
4. Exécutez `npm start` pour démarrer le serveur.

Si configuré correctement, vous devriez voir un message indiquant que le serveur fonctionne correctement et `Database Connected`.

&nbsp;

# Configuration du Côté Client

## Variables d'environnement
D'abord, créez le fichier de variables d'environnement `.env` dans le dossier du client. Le fichier `.env` contient les variables d'environnement suivantes :

- VITE_APP_BASE_URL = `http://localhost:8800` #Note : Changez le port 8800 en votre numéro de port.
- VITE_APP_FIREBASE_API_KEY = `clé API Firebase`

## Étapes pour lancer le client

1. Naviguez dans le répertoire du client `cd client`.
2. Exécutez `npm i` ou `npm install` pour installer les paquets.
3. Exécutez `npm start` pour lancer l'application sur `http://localhost:3000`.
4. Ouvrez [http://localhost:3000](http://localhost:3000) pour le visualiser dans votre navigateur.

&nbsp;

## Pour le support, contactez :

- Email : yao.konan2709@gmail.com