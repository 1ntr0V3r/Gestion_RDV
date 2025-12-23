# Gestion_RDV
Projet MedAppoint (Android Native)
# MedAppoint - Gestion de Cabinet Médical 🏥

##  Présentation du Projet
MedAppoint est une application mobile Android permettant de digitaliser la prise de rendez-vous médicaux. Ce projet est réalisé dans le cadre de notre examen de fin d'études.

L'objectif est de simplifier l'interaction entre les patients, les médecins et le personnel administratif (secrétariat).

---

##  Notre Équipe
* **Chef de Projet / Intégrateur :** [Ton Nom]
* **Développeuse Backend :** Rabab
* **Développeuse Frontend :** Nouha
* **Documentation & QA :** Zouhair

---

##  Fonctionnalités Principales

###  Espace Patient
* Inscription et connexion sécurisée.
* Recherche de médecins et prise de rendez-vous (Consultation/Suivi).
* Historique des rendez-vous et notifications.

###  Espace Médecin
* Consultation du planning quotidien.
* Gestion des disponibilités (créneaux horaires).
* Annulation ou modification de rendez-vous.

###  Espace Admin (Secrétaire)
* Dashboard global de l'activité.
* Gestion des comptes utilisateurs et des plannings.

---

##  Stack Technique

### Backend
* **Framework :** Spring Boot 3
* **Langage :** Java 17+
* **Sécurité :** Spring Security & JWT (JSON Web Token)
* **Base de données :** PostgreSQL

### Frontend (Mobile)
* **Plateforme :** Android Natif
* **Langage :** Java
* **Réseau :** Retrofit 2 (Appels API)
* **Design :** XML Layouts (Material Design)

---

##  Structure du Dépôt
* `/backend` : Code source de l'API Spring Boot.
* `/frontend` : Code source de l'application Android Studio.
* `/docs` : Rapports techniques et schémas de base de données.

---

##  Installation (Développement)
1. **Cloner le projet :** `git clone [URL-DU-REPO]`
2. **Backend :** Configurer la base de données PostgreSQL et lancer l'application via Maven.
3. **Frontend :** Ouvrir le dossier `frontend` dans Android Studio, synchroniser Gradle et lancer sur émulateur.
