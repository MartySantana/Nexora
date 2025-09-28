# Nexora

![Java](https://img.shields.io/badge/Java-21-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2-brightgreen)
![Angular](https://img.shields.io/badge/Angular-18-red)
![Node.js](https://img.shields.io/badge/Node.js-22-green)
![Status](https://img.shields.io/badge/Status-Active-success)

[![Amartha](https://img.shields.io/badge/Backend-Amartha-blue)](https://github.com/MartySantana/Amartha)
[![Lunartha](https://img.shields.io/badge/Frontend-Lunartha-red)](https://github.com/MartySantana/Lunartha)
[![Infra](https://img.shields.io/badge/Infra-Nexora--Infra-grey)](https://github.com/MartySantana/Infra)

---

Nexora est une plateforme personnelle modulaire développée avec **Spring Boot (Amartha)** et **Angular (Lunartha)**.  
Le but est d’apprendre, progresser, et disposer d’un espace regroupant plusieurs outils personnels (tâches, calendrier, etc.).

## 🚀 Architecture
- **[Amartha](https://github.com/MartySantana/Amartha)** : Backend en Spring Boot 3 (Java 21)
- **[Lunartha](https://github.com/MartySantana/Lunartha)** : Frontend en Angular 18
- **[Infra](https://github.com/MartySantana/Infra)** : Infrastructure (Docker, PostgreSQL, CI/CD)

## 📌 Fonctionnalités
- Health check (`/api/health`) fonctionnel entre Lunartha et Amartha
- Proxy Angular configuré pour le dev
- Architecture prête pour ajout de modules (Tasks, Calendar, etc.)

## 🛠️ Roadmap
- [ ] Module "Tasks" : CRUD côté backend et affichage côté frontend
- [ ] Intégration PostgreSQL + Flyway
- [ ] Docker Compose (Amartha + DB + Lunartha)
- [ ] Authentification utilisateur (JWT)

---

✍️ Projet personnel réalisé par **Martin Goazempis**
