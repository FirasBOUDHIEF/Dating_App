# 🥰 DatingApp

**DatingApp** est une application web complète inspirée des plateformes de rencontre.  
Elle permet aux utilisateurs de créer des connexions, chatter en temps réel et gérer leur profil dans une interface moderne et responsive.  

---

## 🚀 Fonctionnalités principales

| Fonctionnalité | Description |
|----------------|-------------|
| 🔐 **Authentification & Autorisation** | JWT + rôles pour sécuriser l’accès |
| 👤 **Gestion des profils utilisateurs** | CRUD complet avec photos |
| 💬 **Messagerie instantanée** | Communication en temps réel via SignalR |
| 🟢 **Système de présence** | Voir qui est en ligne ou offline |
| ❤️ **Likes & Matching** | Liker un utilisateur, voir qui nous a liké, suggestions de match |
| 🔍 **Recherche et filtres** | Filtrer par âge, genre, etc. |
| 📱 **Interface responsive** | UI moderne avec TailwindCSS + DaisyUI |

---

## 🛠 Technologies utilisées

### Frontend
- **Angular 20 (next/rc)** ⚡  
- **TailwindCSS 4 + DaisyUI** 🎨  
- **RxJS** 🔄  
- **SignalR Client** 💬  

### Backend
- **ASP.NET Core Web API** 🌐  
- **Entity Framework Core** 🗄️  
- **SignalR** 💬  
- **JWT Authentication** 🔐  

---

## 🐳 Docker & Base de données
- **SQL Server 2022** exécuté dans un conteneur Docker  
- Configuration définie dans : `docker-compose.yml`  

**Exemple pour lancer Docker :**
```bash
docker-compose up -d
