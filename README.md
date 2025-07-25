# EM_commandement

## Description
Système de gestion tactique COMMANDEMENT_OS v4.2 - Interface de commandement militaire pour la gestion d'escouades, missions et opérations tactiques.

## Structure du Projet

### Fichiers Principaux
- **`index.html`** - Interface État-Major (protégée par authentification)
- **`escouade.html`** - Interface de gestion des escouades (accès public)

### Accès et Authentification

#### Interface État-Major (index.html)
- **Accès protégé** par nom d'utilisateur et mot de passe
- **Identifiants par défaut :**
  - Nom d'utilisateur : `COMMANDANT`
  - Mot de passe : `ETAT-MAJOR-2024`
- **Fonctionnalités :** Gestion complète des missions, escouades, SITREP, rapports

#### Interface Escouades (escouade.html)
- **Accès libre** pour tous les utilisateurs
- **Fonctionnalités :** Configuration et gestion des escouades uniquement

## Fonctionnalités

### Interface État-Major
- 📊 **Dashboard** - Vue d'ensemble des opérations
- 👥 **Gestion des Escouades** - Création, modification, import/export
- 🎯 **Gestion des Missions** - Planification et suivi des opérations
- 📰 **Système SITREP** - Rapports de situation en temps réel
- 📋 **Rapports** - Génération de rapports de mission
- 🚁 **Demandes** - Gestion des renforts et évacuations

### Interface Escouades
- ⚔️ **Sélection d'Escouade** - Choix parmi ALPHA à MIKE
- 👤 **Configuration Personnel** - Gestion des grades et rôles
- 📤 **Export JSON** - Compatible avec l'import État-Major
- ✂️ **Scission d'Équipe** - Division en équipes ASSO/SOUTIEN

## Utilisation

### Démarrage
1. Ouvrir `index.html` dans un navigateur web
2. Saisir les identifiants d'authentification
3. Accéder à l'interface État-Major complète

### Accès Escouades
1. Cliquer sur le lien "Interface Escouades (Public)" depuis la page de connexion
2. OU ouvrir directement `escouade.html`

### Workflow Recommandé
1. **Configuration des Escouades** via `escouade.html`
2. **Export JSON** des escouades configurées
3. **Import dans l'État-Major** via `index.html`
4. **Création et gestion des missions**

## Compatibilité
- ✅ **Navigateurs modernes** (Chrome, Firefox, Safari, Edge)
- ✅ **Responsive Design** - Compatible mobile et desktop
- ✅ **iOS Safari** - Optimisé pour appareils Apple
- ✅ **Mode Hors-ligne** - Fonctionne sans connexion internet

## Stockage des Données
- **LocalStorage** - Sauvegarde automatique des données
- **SessionStorage** - Gestion de l'authentification
- **Export/Import JSON** - Sauvegarde et partage des configurations

## Sécurité
- 🔐 **Authentification simple** pour l'interface État-Major
- 🔒 **Session temporaire** - Déconnexion automatique à la fermeture
- 🚪 **Bouton de déconnexion** disponible dans l'interface

## Support
Interface développée pour les besoins tactiques et opérationnels. 
Système autonome ne nécessitant aucune installation ou serveur externe.

---
**COMMANDEMENT_OS v4.2** - Gestionnaire Tactique
