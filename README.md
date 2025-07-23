# 🧩 Memory Game App

Un petit jeu de Memory réalisé avec **React**, **Vite** et **Electron**.  
Développé pour apprendre à packager une app de bureau multiplateforme.

---

## 🚀 Fonctionnalités

- 🎮 Jeu de Memory basique avec React
- ⚡ Frontend ultra-rapide grâce à Vite
- 🖥️ Déploiement natif grâce à Electron + Electron Forge
- 📦 Emballé avec `asar` pour plus de sécurité

---

## 📂 Structure du projet

```
memory-game-app/
├── src/
├── public/ 
├── main.js 
├── forge.config.cjs 
├── vite.config.js 
├── dist/ 
└── out/ 
```
---

## 🧑‍💻 Développement

```bash
# Installation des dépendances
npm install

# Lancer le frontend Vite
npm run dev

# Lancer Electron avec le serveur Vite
npm run start

# Pour générer une version installable pour macOS, Windows ou Linux :
npm run make

Les fichiers se trouvent dans le dossier out/.
Les dernières versions packagées se trouvent dans la section Releases.

✨ Merci !

Projet fait pour s'amuser, apprendre et partager.
Créé avec ❤️ par Stella.