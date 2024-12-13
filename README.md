# GESTION_DE_PARC-GLPI
Ce repository contient un projet de gestion de parc informatique utilisant GLPI. Il comprend les configurations, scripts et documentations nécessaires pour le déploiement et la maintenance de la solution GLPI, visant à faciliter le suivi des actifs et des interventions au sein du parc informatique.



![Bannière](Image/glpi.jpg)

[![GLPI](https://img.shields.io/badge/GLPI-009688?style=flat-square&logo=glpi&logoColor=white)](https://glpi-project.org/) [![LDAP](https://img.shields.io/badge/LDAP-000080?style=flat-square&logo=ldap&logoColor=white)](https://ldap.com/) [![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white)](https://www.mysql.com/) [![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)](https://httpd.apache.org/) [![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)](https://www.php.net/)

---

## 📚 **Description**

Ce repository propose un guide complet pour installer, configurer et gérer un parc informatique avec **GLPI** (*Gestion Libre de Parc Informatique*). Il fournit des instructions détaillées et illustrées pour :

- 📋 **Administrer le matériel et les logiciels**.  
- 🛠️ **Gérer les tickets d’incident**.  
- 🔒 **Configurer l’intégration LDAP**.  
- 📊 **Superviser les fournisseurs et les budgets**.  

Cet outil est destiné aux administrateurs réseau et responsables IT souhaitant centraliser et automatiser la gestion de leur parc informatique.

---

## 💡 **Introduction**

La gestion d’un parc informatique requiert des outils performants pour centraliser et automatiser les opérations. **GLPI** est une solution open-source permettant :

- 📊 **L’inventaire des équipements**.  
- 🔧 **La gestion des tickets d’incident**.  
- 🏢 **Le suivi des fournisseurs et des budgets**.  
- 🔒 **L’intégration avec un annuaire LDAP**.  

Ce guide vous accompagne dans la mise en place de **GLPI** pour optimiser ces tâches essentielles.

---

## ⚙️ **Prérequis**

### **Matériels et Logiciels**

- **Serveur Web** : Apache, Nginx  
- **Base de Données** : MySQL/MariaDB  
- **Langage** : PHP 7.x ou supérieur  
- **Système d’Exploitation** : Linux (Ubuntu, CentOS)  

### **Extensions PHP Requises**

- `pdo_mysql`  
- `curl`  
- `gd`  
- `xml`  
- `ldap` (pour l’intégration LDAP)  

---

## 🚀 **Installation de GLPI**

1. **Télécharger GLPI** :  
   ```bash
   wget https://github.com/glpi-project/glpi/releases/download/9.5.5/glpi-9.5.5.tgz
   ```

2. **Extraire l’archive** :  
   ```bash
   tar -xvzf glpi-9.5.5.tgz
   ```

3. **Déplacer les fichiers** :  
   ```bash
   sudo mv glpi /var/www/html/
   ```

4. **Configurer les permissions** :  
   ```bash
   sudo chown -R www-data:www-data /var/www/html/glpi
   ```

5. **Accéder à l’interface** :  
   Ouvrez `http://<adresse-du-serveur>/glpi` et suivez les instructions d’installation.

---

## 🔧 **Configuration Initiale**

1. **Paramétrer la Base de Données**.  
2. **Créer des utilisateurs administrateurs**.  
3. **Configurer le réseau et les plugins nécessaires**.  

---

## 🛠️ **Fonctionnalités de GLPI**

- **Inventaire des équipements** : Matériel, logiciels, périphériques.  
- **Gestion des incidents** : Création, assignation et suivi des tickets.  
- **Intégration LDAP** : Synchronisation avec un annuaire LDAP.  
- **Suivi financier** : Gestion des fournisseurs et budgets.  

---

## 🔒 **Sécurité et Bonnes Pratiques**

- **Sauvegarder régulièrement** la base de données.  
- **Mettre à jour** GLPI et ses plugins.  
- **Restreindre l’accès** aux interfaces d’administration.  

---

## 📂 **Structure du Repository**

- **`Directives_Rapport_GLPI/`** : Instructions et rapports pratiques.  
- **`Doc/`** : Documentation détaillée et choix techniques.  
- **`Img/`** : Captures d’écran et illustrations.  
- **`README.md`** : Guide principal.  

---

## 📝 **Ressources Supplémentaires**

- **Site Officiel** : [GLPI Project](https://glpi-project.org)  
- **Documentation** : [GLPI Docs](https://glpi-docs.readthedocs.io)  

---

## ✍️ **Auteur**

**Adrien VENTRE**  
🗓 13 Décembre 2024  

---
