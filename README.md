# 🚀 TalentPool - Interface Utilisateur

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Status](https://img.shields.io/badge/status-en%20développement-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

> Une interface utilisateur moderne et intuitive pour la plateforme de recrutement TalentPool, développée en JavaScript natif pour une consommation efficace de l'API TalentPool.

![TalentPool Banner](https://via.placeholder.com/800x200?text=TalentPool+Platform)

## 📋 Table des matières

- [Aperçu](#-aperçu)
- [Fonctionnalités](#-fonctionnalités)
- [Technologies](#-technologies)
- [Installation](#-installation)
- [Structure du projet](#-structure-du-projet)
- [Consommation de l'API](#-consommation-de-lapi)
- [Utilisation](#-utilisation)
- [Captures d'écran](#-captures-décran)
- [Équipe](#-équipe)
- [Contribution](#-contribution)
- [Licence](#-licence)

## 🌟 Aperçu

TalentPool est une plateforme de recrutement qui connecte les recruteurs et les candidats. Cette interface utilisateur est développée en JavaScript natif, optimisée pour consommer l'API TalentPool de manière efficace et performante, offrant une expérience fluide et réactive.

## ✨ Fonctionnalités

### 📢 Gestion des Annonces
- 📋 Affichage de la liste des annonces avec pagination
- 📝 Création, modification et suppression d'annonces via l'API
- 🔍 Recherche et filtrage avancés
- 👁️ Vue détaillée des annonces

### 📬 Gestion des Candidatures
- 📤 Formulaire d'envoi de candidature avec upload de CV et lettre de motivation
- 📋 Liste des candidatures envoyées avec option de retrait
- 🔍 Filtrage des candidatures pour les recruteurs
- 📄 Prévisualisation des documents

### 📊 Suivi des Candidatures
- 🚦 Affichage du statut des candidatures (en attente, acceptée, refusée)
- 🔔 Système de notifications visuelles
- 📱 Mises à jour en temps réel via l'API

### 🔐 Authentification et Sécurité
- 🔑 Connexion sécurisée par email et mot de passe
- 👤 Inscription avec choix de rôle (candidat ou recruteur)
- 🔄 Réinitialisation du mot de passe
- 🛡️ Protection des routes sensibles
- 🔒 Gestion des tokens JWT

### 📈 Statistiques et Rapports
- 📊 Tableau de bord pour les recruteurs
- 📉 Visualisations graphiques des données
- 📑 Page d'administration avec résumé des activités
- 📤 Export des données

## 💻 Technologies

- 🌐 HTML5, CSS3, JavaScript ES6+ natif
- 🔄 Consommation d'API REST avec Fetch API / Axios
- 🎨 CSS personnalisé avec variables CSS
- 📱 Design responsive avec Media Queries
- 🔒 Gestion de l'authentification JWT
- 📦 Bundler: Webpack / Parcel
- 🧪 Tests: Jest
- 🚀 Déploiement: Vercel / Netlify

## 🚀 Installation

```bash
# Cloner le dépôt
git clone https://github.com/votre-organisation/talentpool-ui.git

# Accéder au répertoire
cd talentpool-ui

# Installer les dépendances
npm install
# ou
yarn install

# Configurer les variables d'environnement
cp .env.example .env
# Éditer le fichier .env avec l'URL de l'API

# Lancer le serveur de développement
npm run dev
# ou
yarn dev