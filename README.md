<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=87CEEB&center=true&vCenter=true&width=440&lines=t-+Salut%2C+je+suis+Cloud+%F0%9F%91%8B;D%C3%A9veloppeur+Junior;Passionn%C3%A9+de+S%C3%A9curit%C3%A9" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</p>

<div align="center">
  
  ![Status](https://img.shields.io/badge/statut-42_SCHOOL-87CEEB?style=for-the-badge)
  ![Focus](https://img.shields.io/badge/focus-s%C3%A9curit%C3%A9-B0D4F1?style=for-the-badge)
  
</div>

---

<img align="right" alt="Coding" width="300" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif">

### À propos

Actuellement en formation pour intégrer l'**École 42** (Piscine en septembre 2025 → Retry Piscine 2026)
Ce GitHub sert à illustrer toute ma progression, depuis mes debuts en tant que developpeur junior jusqu'a, je l'espere developpeur senior.

**Mes centres d'intérêt :**
- 🔒 Cybersécurité & Ethical Hacking
- 🐧 Systèmes Linux & Programmation Bas Niveau
- 🔐 Création d'outils sécurisés et respectueux de la vie privée
- 📟 Création de CLI (mini games / outils tout types)


---

### 🛠️ Stack & Outils

<div align="center">

![C](https://img.shields.io/badge/C-87CEEB?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-6DB3D4?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-B0D4F1?style=for-the-badge&logo=linux&logoColor=333)
![Git](https://img.shields.io/badge/Git-5A9FCA?style=for-the-badge&logo=git&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-87CEEB?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-6DB3D4?style=for-the-badge&logo=css3&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-5A9FCA?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Vim](https://img.shields.io/badge/Vim-87CEEB?style=for-the-badge&logo=vim&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-6DB3D4?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![OSINT](https://img.shields.io/badge/OSINT-B0D4F1?style=for-the-badge&logo=searchengineland&logoColor=white)
![CSINT](https://img.shields.io/badge/CSINT-5A9FCA?style=for-the-badge&logo=hackthebox&logoColor=white)

</div>

---

### 📦 Projets Python

<details>
<summary><b>🔐 PASSWORLD v2</b> - Gestionnaire de Mots de Passe</summary>

<br>

**📊 Statut**

![Progression](https://img.shields.io/badge/Statut-Termine-87CEEB?style=for-the-badge)

**Description**

Gestionnaire de mots de passe en ligne de commande avec chiffrement local. Refonte complete de la v1 pour apprendre la POO et la manipulation de fichiers JSON.

**Fonctionnalites**

- Ajout/suppression/recherche de mots de passe
- Generateur de mots de passe personnalisable
- Validation des regles de securite (longueur, majuscules, chiffres, symboles)
- Chiffrement XOR + Base64
- Sauvegarde en JSON
- Detection des doublons (insensible a la casse)
- Blacklist de mots de passe courants

**Architecture**

7 fichiers Python structures en POO :
- `Crypto` : chiffrement/dechiffrement
- `Validator` : verification des regles
- `Generator` : creation aleatoire
- `Manager` : gestion CRUD
- `PasswordApp` : interface menu
- `config.py` : constantes
- `main.py` : point d'entree

**Ce que j'ai appris**

POO, manipulation JSON, chiffrement de base, validation d'entrees, gestion d'erreurs, architecture modulaire.

**Evolution v1 → v2**

| v1 | v2 |
|----|---|
| Code procedural | POO (7 classes) |
| Pas de securite | Chiffrement XOR + Base64 |
| Pas de validation | Regles strictes + blacklist |
| Interface basique | Menu avec gestion erreurs |

**A ameliorer pour v3**

- Ajouter AES-256 au lieu de XOR
- Passer de JSON a SQLite
- Permettre d'ajouter des mots a la blacklist depuis l'interface
- Ajouter un historique des modifications
- Creer une interface graphique simple (KIVY)
- Implementer l'authentification 2FA

**Technologies**

Python 3.13 • JSON • XOR + Base64 • POO

**📂 Lien GitHub** → [PASSWORLD v2](https://github.com/silverfish000/GESTIONNAIRE_MDP_v2)

---

</details>
<details>
<summary><b>🔓 PASSWORD v1</b> - Version Initiale (Projet de référence)</summary>

<br>

**📊 Statut**

![Statut](https://img.shields.io/badge/Statut-Version_Initiale-B0D4F1?style=for-the-badge)

**🎯 Objectif**

Premier système de gestion de mots de passe en Python avec stockage local. Ce projet correspond à mes débuts en développement et sert de base fonctionnelle pour mesurer mon évolution à travers les versions futures.

**⚠️ Caractéristiques**

- ✅ Système basique d'ajout/suppression de mots de passe
- ⚠️ Fonctionnalités limitées (projet d'apprentissage)
- ❌ Pas de chiffrement (stockage en clair)
- ❌ Pas d'architecture POO
- ❌ Interface CLI minimaliste

**📈 Évolution v1 → v2**

| Aspect | v1 | v2 |
|--------|----|----|
| Architecture | Procédurale | POO (7 classes) |
| Sécurité | ❌ Aucune | ✅ Chiffrement XOR + Base64 |
| Interface | Basique | CLI intuitive |
| Validation | ❌ Non | ✅ Validator |
| Génération | ❌ Non | ✅ Generator personnalisable |

**🛠️ Technologies**

![Python](https://img.shields.io/badge/Python-87CEEB?style=flat-square&logo=python&logoColor=white)
![Basique](https://img.shields.io/badge/Projet_Basique-B0D4F1?style=flat-square)

**📂 Lien GitHub** → [PASSWORD v1](https://github.com/silverfish000/projet-n1)

---

</details>

<div align="center">
<img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExYmg1NWhwZDB0aGRueHNvZW93dGpzcWozeGJoaWh5OHVrZTBlc3lqZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3wr2cnwlghNomDeN9W/giphy.gif" width="300">
</div>

---

### 📊 Statistiques GitHub

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=cloudking-42&theme=react-dark&hide_border=true&bg_color=0d1117&color=87CEEB&line=5A9FCA&point=B0D4F1&area=true&area_color=6DB3D4"/>
</div>

---

### 🌐 Contact

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-silverfish000-5A9FCA?style=for-the-badge&logo=github&logoColor=white)](https://github.com/silverfish000)
[![Discord](https://img.shields.io/badge/Discord-silver000__0__-87CEEB?style=for-the-badge&logo=discord&logoColor=white)](https://discordapp.com/users/silver000_0_)
[![Dev.to](https://img.shields.io/badge/dev.to-silver__0__-6DB3D4?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/silver_0_)
[![CodinGame](https://img.shields.io/badge/CodinGame-Silver000-B0D4F1?style=for-the-badge&logo=codingame&logoColor=333)](https://www.codingame.com/profile/58d9710057d474c5fa5b81ac2c2756a83562207)

</div>

---

<div align="center">
  
  ![Profile Views](https://komarev.com/ghpvc/?username=silverfish000&color=87CEEB&style=for-the-badge)
  
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:B0D4F1,50:87CEEB,100:5A9FCA&height=100&section=footer"/>
  
</div>
