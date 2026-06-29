# Application de Gestion Commerciale 📊

Application complète de gestion commerciale permettant de gérer :
- 📦 **Fournisseurs** avec solde
- 👥 **Clients** avec coordonnées
- 📄 **Articles** vendus à la tonne
- 🚚 **Lieux de Livraison** avec tarifs
- 💰 **Commandes et Facturation**

## Stack Technologique

- **Backend** : Node.js + Express + MongoDB
- **Frontend** : React + Tailwind CSS
- **Base de données** : MongoDB
- **Authentification** : JWT

## Installation

### Prérequis
- Node.js 16+
- MongoDB
- npm ou yarn

### Installation locale

```bash
# Cloner le repository
git clone https://github.com/Heurdj/app-gestion-commerciale.git
cd app-gestion-commerciale

# Installation des dépendances backend
cd server
npm install

# Installation des dépendances frontend
cd ../client
npm install
```

### Démarrage

```bash
# Terminal 1 - Backend
cd server
npm start

# Terminal 2 - Frontend
cd client
npm run dev
```

L'application sera accessible sur http://localhost:3000

## Fonctionnalités

### 🏢 Gestion des Fournisseurs
- Créer/Éditer/Supprimer fournisseurs
- Tracker le solde
- Historique des transactions

### 👤 Gestion des Clients
- Base de données clients
- Adresses de livraison
- Historique des commandes

### 📦 Catalogue d'Articles
- Gestion des articles par tonne
- Prix unitaire
- Stock disponible

### 🚚 Lieux de Livraison
- Enregistrement des destinations
- Tarifs de livraison
- Calcul automatique des frais

### 💼 Commandes et Facturation
- Création de commandes
- Génération de factures
- Suivi de paiement

## License

MIT