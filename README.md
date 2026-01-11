# 📦 Quick Livraison - Employee Management System

![Laravel](https://img.shields.io/badge/Laravel-10-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![AdminLTE](https://img.shields.io/badge/AdminLTE-3-brightgreen?style=for-the-badge)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

## 📖 À propos du projet (Context)

Ce projet a été réalisé durant mon **stage technique** au sein de la société **Quick Livraison**.
L'objectif était de développer une solution digitale pour faciliter la gestion des ressources humaines (RH) et le suivi des employés (livreurs et staff administratif).

Il permet de centraliser les informations des employés et d'automatiser les tâches administratives quotidiennes.

## ✨ Fonctionnalités Clés

* **Tableau de bord RH :** Vue d'ensemble sur le nombre d'employés, départements et statistiques.
* **Gestion des Employés (CRUD) :** Ajout, modification et archivage des profils (Livreurs, Admin, Staff).
* **Suivi de Carrière :** Gestion des contrats, congés et salaires.
* **Recherche & Filtrage :** Recherche rapide d'un employé par département ou poste.
* **Interface Admin :** Panneau de contrôle sécurisé basé sur **AdminLTE**.

## 🛠️ Technologies Utilisées

* **Backend :** Laravel 10 (PHP 8.1+)
* **Frontend :** Blade Templates, Bootstrap 5
* **Thème UI :** AdminLTE 3
* **Base de données :** MySQL
* **Outils de développement :** Composer, Vite, Git

## 🚀 Installation

Si vous souhaitez tester le projet en local :

1.  **Cloner le repo :**
    ```bash
    git clone [https://github.com/votre-username/quick-livraison-rh.git](https://github.com/votre-username/quick-livraison-rh.git)
    ```
2.  **Installer les dépendances :**
    ```bash
    composer install
    npm install
    ```
3.  **Configurer l'environnement (.env) :**
    ```bash
    cp .env.example .env
    php artisan key:generate
    ```
4.  **Base de données :**
    Créez une base de données MySQL et lancez les migrations :
    ```bash
    php artisan migrate
    ```
5.  **Lancer le serveur :**
    ```bash
    php artisan serve
    ```

## 👨‍💻 Auteur

**Youssef El Mohammady**
* Stagiaire Développeur Full Stack
* [Mon Profil LinkedIn]("Youssef El mohammady")

---
*Projet réalisé dans le cadre du stage OFPPT @ Quick Livraison.*