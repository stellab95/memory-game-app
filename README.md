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

```
---

# 🛠️ Installation

Merci de télécharger **Memory Game** !  
Voici comment lancer le jeu sur **macOS** et **Windows**.

---

## 🍏 macOS

**⚠️ Comme l’app n’est pas signée, Gatekeeper peut dire qu’elle est corrompue ou bloquée.**

### ✅ Débloquer l’app

**Méthode rapide :**

1️⃣ Télécharge et dézippe `Memory.app`  
2️⃣ Ouvre le **Terminal**  
3️⃣ Tape cette commande :

```bash
xattr -cr /Chemin/vers/Memory.app


## ✨ Merci !

Projet fait pour s'amuser, apprendre et partager.
Créé avec ❤️ par Stella.