# 📝 Mini Projet – API CRUD Node.js / Express / MongoDB
## Description du projet

Ce mini-projet est une API RESTful développée avec Node.js, Express et MongoDB (Mongoose).
Elle permet de gérer des articles (posts) à travers des opérations CRUD :
- Create → Ajouter un nouveau post
- Read → Consulter un ou plusieurs posts
- Update → Modifier un post existant
- Delete → Supprimer un post

L’objectif est de comprendre la structure d’un backend simple en Express, la gestion des routes et l’interaction avec une base de données MongoDB.

## ⚙️ Technologies utilisées

- Node.js : environnement d’exécution JavaScript côté serveur
- Express.js : framework minimaliste pour la création d’API REST
- MongoDB : base de données NoSQL pour le stockage des données
- Mongoose : ODM pour interagir avec MongoDB
- Slugify : pour générer des slugs lisibles à partir des titres

## 🚀 Installation et exécution

### 1️⃣ Cloner le projet
<pre>git clone https://github.com/SirineRaies/BlogAPICrud.git</pre>
<pre>cd BlogAPICrud</pre>

### 2️⃣ Installer les dépendances
<pre>npm i </pre>

### 3️⃣ Configurer la base de données

- Dans config/config.js, ajoute ton URL MongoDB :
  
  <pre>module.exports = {
  DB_URL: "mongodb://localhost:27017/miniProjetDB"
}</pre>

### 4️⃣ Lancer le serveur
<pre>npm start</pre>


## 🧩 Endpoints disponibles

| Méthode | Route | Description |
|----------|--------|-------------|
| **POST** | `/api/posts` | Créer un nouveau post |
| **GET** | `/api/posts` | Afficher tous les posts |
| **GET** | `/api/posts/:id` | Récupérer un post par ID |
| **PUT** | `/api/posts/:id` | Mettre à jour un post |
| **DELETE** | `/api/posts/:id` | Supprimer un post |



## 👩‍💻 Auteur

Sirine Raies : Étudiante en Génie Informatique à l’École Polytechnique de Sousse
Projet réalisé dans le cadre d’un mini-projet de classe pour la pratique du backend avec Node.js.
