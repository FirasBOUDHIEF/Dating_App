📝 Description

DatingApp est une application web complète inspirée des plateformes de rencontre.
Elle permet aux utilisateurs de :

S’inscrire et se connecter via un système d’authentification sécurisé (JWT).

Gérer leur profil (informations personnelles, photos, préférences).

Parcourir les autres membres et consulter leurs profils.

Envoyer et recevoir des messages en temps réel grâce à SignalR.

Voir l’état de connexion des utilisateurs (online/offline, présence en direct).

Utiliser une interface moderne et responsive grâce à Angular + TailwindCSS + DaisyUI.


Technologies utilisées
Frontend

Angular 20 (next/rc)

TailwindCSS 4 + DaisyUI (UI moderne et responsive)

RxJS (programmation réactive)

SignalR Client (temps réel)

Backend 

ASP.NET Core Web API

Entity Framework Core (accès base de données)

SignalR (communication en temps réel)

JWT Authentication



🚀 Fonctionnalités principales (mise à jour)

🔐 Authentification & Autorisation (JWT + rôles)

👤 Gestion des profils utilisateurs (CRUD + photos)

💬 Messagerie instantanée (SignalR)

🟢 Système de présence (voir qui est connecté)

❤️ Système de Likes & Matching (liker un utilisateur, voir qui nous a liké, suggestions de match)

🔍 Recherche et filtres (par âge, genre, etc.)

📱 Interface responsive avec Tailwind + DaisyUI


Docker – Base de données SQL Server

Le projet utilise SQL Server 2022 comme base de données, exécutée dans un conteneur Docker.
La configuration est définie dans le fichier docker-compose.yml :