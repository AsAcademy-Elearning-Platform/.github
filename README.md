# AsaCademy - Plateforme d'Apprentissage en Ligne

## 📚 Aperçu

AsaCademy est une plateforme complète d'apprentissage en ligne composée de trois principaux projets qui fonctionnent ensemble pour fournir une expérience d'apprentissage fluide et interactive.

## 🏗️ Architecture du Projet

### 1. Frontend (Angular)
- **Dossier**: `asacademyFront/`
- **Technologies**: Angular 17, TypeScript, RxJS
- **Rôle**: Interface utilisateur réactive et interactive
- **Fonctionnalités clés**:
  - Navigation intuitive entre les cours
  - Tableau de bord étudiant/enseignant
  - Lecteur de contenu multimédia
  - Système d'authentification

### 2. Backend Principal (Spring Boot)
- **Dossier**: `asacademyBack/`
- **Technologies**: Java 17, Spring Boot, Spring Security, JPA/Hibernate
- **Rôle**: Gestion des données principales et logique métier
- **Fonctionnalités clés**:
  - Gestion des utilisateurs et rôles
  - Gestion des cours et du contenu pédagogique
  - Système d'évaluation et de suivi
  - API REST sécurisée

### 3. Microservice FastAPI
- **Dossier**: `asacademyFastApi/`
- **Technologies**: Python, FastAPI, SQLAlchemy
- **Rôle**: Services spécialisés et traitement en temps réel
- **Fonctionnalités clés**:
  - Traitement des médias
  - Analyse des données d'apprentissage
  - Intégrations avec services externes
  - API haute performance

## 🚀 Démarrage Rapide

1. **Cloner le dépôt**
   ```bash
   git clone <url-du-depot>
   cd asacademy
   ```

2. **Démarrer les services**
   ```bash
   # Démarrer le backend Spring Boot
   cd asacademyBack
   mvn spring-boot:run

   # Démarrer le service FastAPI
   cd ../asacademyFastApi
   uvicorn app.main:app --reload

   # Démarrer le frontend Angular
   cd ../asacademyFront
   ng serve
   ```

3. **Accès aux applications**
   - Frontend: http://localhost:4200
   - API Spring Boot: http://localhost:8080
   - API FastAPI: http://localhost:8000
   - Documentation FastAPI: http://localhost:8000/docs

## 🔧 Configuration

Chaque projet contient son propre fichier README avec des instructions détaillées de configuration et de déploiement.

## 🤝 Contribution

Veuillez vous référer aux directives de contribution spécifiques à chaque projet.

## 📄 Licence

[À spécifier selon la licence choisie pour le projet]

---

Développé avec ❤️ par l'équipe AsaCademy
