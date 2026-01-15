MedAppoint - Système de Gestion Médicale Full-Stack
Présentation du Projet
MedAppoint est une solution numérique intégrée (Mobile + API) permettant de digitaliser la prise de rendez-vous médicaux. Ce projet repose sur une architecture client-serveur moderne où chaque membre de l'équipe a contribué de manière transversale à l'ensemble de la chaîne de développement.

Notre Équipe (Full-Stack Developers)
Nous avons adopté une méthode de travail agile où chaque développeur a participé à la fois au Frontend, au Backend et à la Gestion des Données :

Amine : Développeur Full-Stack & Architecture Système.

Rabab : Développeuse Full-Stack & Conception API.

Nouha : Développeuse Full-Stack & UI/UX Design.

Zouhair : Développeur Full-Stack & Qualité Logicielle.

Stack Technique
Frontend Mobile : Android Natif (Java) avec Retrofit 2 pour une communication fluide avec le serveur.

Backend API : Spring Boot 3 (Java) assurant la logique métier et la sécurité des données.

Base de Données : PostgreSQL géré via Docker pour garantir un environnement de développement stable et isolé.

Outils Pro : IntelliJ IDEA (Backend) et Android Studio (Frontend).

Installation Rapide
1. Préparation de la Base (Docker)
Lancez Docker Desktop, puis exécutez la commande suivante à la racine :

Bash

docker-compose up -d
2. Lancement du Serveur (IntelliJ IDEA)
Ouvrez le projet /backend dans IntelliJ IDEA.

Le serveur se connectera automatiquement à PostgreSQL sur le port 5432.

Exécutez MedAppointBackendApplication.java.

3. Lancement du Mobile (Android Studio)
Ouvrez le projet /app dans Android Studio.

Assurez-vous que l'adresse IP du serveur est correctement configurée pour l'émulateur (10.0.2.2).

Identifiants de Démo
Admin : admin@test.com / admin123

Médecin : doctor@test.com / doc123

Patient : patient@test.com / pat123
