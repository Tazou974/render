# 🚀 RPI Radio WebSocket Server - Render Deployment

## 📁 Fichiers pour Render.com

Ce dossier contient tous les fichiers prêts pour le déploiement sur Render.com :

- **`server.js`** - Serveur WebSocket principal
- **`package.json`** - Configuration et dépendances
- **`README.md`** - Ce fichier

## 🎯 Instructions de déploiement

### 1. Créer un compte Render
- Allez sur https://render.com
- Créez un compte gratuit

### 2. Nouveau Web Service
- Cliquez "New +" → "Web Service"
- Sélectionnez "Build and deploy from a Git repository"
- Ou uploadez ces fichiers directement

### 3. Configuration
- **Build Command**: `npm install`
- **Start Command**: `npm start`
- **Environment**: Node
- **Plan**: Free (0$/mois)

### 4. URL finale
Votre serveur sera accessible sur :
```
https://votre-nom-projet.onrender.com
```

WebSocket URL :
```
wss://votre-nom-projet.onrender.com/chat
```

## ✅ Fonctionnalités

- ✅ Chat temps réel
- ✅ Gestion des utilisateurs
- ✅ Messages système
- ✅ Interface web de statut
- ✅ SSL automatique (wss://)
- ✅ Health check endpoint

## 🔧 Test local

```bash
npm install
npm start
```

Le serveur démarrera sur http://localhost:10000

## 📞 Support

Une fois déployé, votre chat RPI Radio sera 100% fonctionnel !
