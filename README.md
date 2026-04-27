# 👥 Power BI - Modélisation de Données RH, KPIs & Dashboards Interactifs

<p align="center">
  <img width="1189" alt="Capture d’écran RH-01" src="https://github.com/user-attachments/assets/e82a47d0-a06b-4f48-b393-81a4eaadc79e" />
</p>

<p align="center">
  <img width="1187" alt="Capture d’écran RH-02" src="https://github.com/user-attachments/assets/40f20d77-ac30-4a84-b762-49c5faef2bc2" />
</p>

<p align="center">
  <img width="1184" alt="Capture d’écran RH-03" src="https://github.com/user-attachments/assets/bc01ca0c-33c1-4ae0-b1d2-78df57fa2564" />
</p>

<p align="center">
  <img width="1190" alt="Capture d’écran RH-04" src="https://github.com/user-attachments/assets/b89fb72b-621f-4358-8468-2c5052a17eb3" />
</p>

## 📝 Présentation du Projet
Ce projet consiste à concevoir un tableau de bord Power BI interactif de niveau professionnel pour l'analyse des ressources humaines (RH). L'objectif est de fournir à la direction un outil décisionnel permettant de piloter la main-d'œuvre, d'anticiper le **turnover** et d'analyser la **rétention des talents** via une interface utilisateur optimisée.

## 🎯 Objectifs du Projet
* **Modélisation** : Structurer les données selon un schéma en étoile (*Star Schema*).
* **Analyse DAX** : Créer des mesures avancées pour les indicateurs RH essentiels.
* **Reporting Multi-pages** : Concevoir des vues dédiées (Effectifs, Rétention, Turnover).
* **Interactivité** : Développer des fonctionnalités avancées (panels de filtres, tooltips).
* **Design UX/UI** : Appliquer une identité visuelle cohérente et professionnelle.

## 🛠️ Outils et Technologies
* **Power BI Desktop** : Développement du modèle et des rapports.
* **Power Query** : Importation, nettoyage et transformation des données (ETL).
* **Langage DAX** : Création des calculs et mesures métier complexes.
* **Jira** : Gestion et planification des tâches.

---

## 🚀 Étapes de Réalisation

### 1. Préparation et Modélisation 🏗️
* **Nettoyage** : Traitement des fichiers CSV (*People Data*, *Employment History*) via Power Query.
* **Star Schema** : Mise en place d'une table de faits (**People Fact**) reliée à 8 tables de dimension (Département, Job Level, Démographie, etc.).
* **Normalisation** : Calcul des âges, conversion des salaires et gestion des hiérarchies managériales.

### 2. Développement des Indicateurs (DAX) 📈
Création d'une table de mesures dédiée regroupant les KPIs critiques :
* **Headcount** : Suivi de l'effectif total actuel.
* **Turnover** : Analyse du taux de rotation du personnel.
* **Retention** : Mesure de la capacité à conserver les talents.

### 3. Conception du Dashboard Multi-pages 🎨
* **Page Headcount** : Analyse démographique (genre, âge, ethnie) et répartition par département ou ville.
* **Page Rétention** : Visualisation de la fidélisation via des graphiques de pente (*Slope charts*) et paramètres de champs.
* **Page Turnover** : Évolution temporelle des départs et analyse des motifs de fin de contrat.

### 4. Interactivité et UX Avancé 🖱️
* **Panel de segments** : Utilisation de *Bookmarks* pour un menu de filtres escamotable (icône hamburger).
* **Tooltips dynamiques** : Affichage des détails d'un employé (salaire, date d'embauche) au survol des visuels.
* **Landing Page** : Interface d'accueil avec navigation fluide et effets visuels au survol (*hover*).

---
*Projet réalisé dans l'optique d'optimiser la gestion du capital humain via la Data.*
