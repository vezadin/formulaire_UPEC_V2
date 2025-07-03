# Formulaire avec Captcha

Un projet PHP simple qui permet d’envoyer un formulaire protégé par un captcha (IconCaptcha), afin d’éviter les soumissions automatisées.

## 🧰 Technologies utilisées

- PHP
- HTML / CSS
- IconCaptcha
- Composer
- Docker / Docker Compose

## 🚀 Fonctionnalités

- Formulaire de contact avec :
  - Nom
  - Prénom
  - Email
  - Téléphone
  - Demande
- Protection contre les bots grâce à [IconCaptcha](https://www.fabianwennink.nl/projects/IconCaptcha/)
- Affichage dynamique des messages de validation
- Déploiement local simple avec Docker

## 📦 Installation (sans Docker)

1. **Cloner le projet** :
   ```bash
   git clone https://github.com/vezadin/formulaire_avec_captcha.git
   cd formulaire_avec_captcha
2. **Lancer le serveur (2 options possibles)** :

**Avec Docker**
Lancer les conteneurs :

    docker compose up --build

Arrêter les conteneurs :
    
    docker compose down

**Avec PHP**:
    
    php -S localhost:8000
