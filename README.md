# 📊 Tableau de bord de pilotage de projets avec Power BI

## 📌 Présentation

Ce projet a été réalisé dans le cadre de la formation **Data Analyst OpenClassrooms**.

L'objectif est de concevoir un **tableau de bord interactif sous Microsoft Power BI** permettant au service PMO de l'entreprise fictive **Sanitoral** de suivre l'avancement de ses projets, contrôler les coûts, identifier les retards et faciliter la prise de décision des directeurs.

Le tableau de bord est entièrement dynamique et peut être mis à jour automatiquement grâce à **Power Query**.

---

## 🎯 Objectifs du projet

Le tableau de bord répond aux besoins suivants :

- Suivre l'avancement des projets.
- Comparer les budgets prévus et réels.
- Identifier rapidement les dépassements de budget.
- Détecter les retards de réalisation.
- Suivre les livrables.
- Analyser les projets par pays, région et type de projet.
- Faciliter la prise de décision grâce à des indicateurs clés (KPI).

---

## 🛠️ Technologies utilisées

- Microsoft Power BI
- Power Query
- DAX
- Excel

---

## 📈 Contenu du tableau de bord

Le rapport est composé de quatre pages :

### 📄 Page 1 – Tableau de bord de pilotage

Vue d'ensemble du portefeuille de projets avec :

- Nombre total de projets
- Budget prévu
- Budget réel
- Écart budgétaire
- Nombre de projets en alerte
- Comparaison des budgets
- Comparaison des durées
- Comparaison des livrables
- Carte mondiale des projets
- Répartition par type de projet

---

### 📄 Page 2 – Analyse détaillée

Analyse projet par projet comprenant :

- Budget prévu / réel
- Durée prévue / réelle
- Écart budgétaire (%)
- Écart de durée (%)
- Statut du projet
- Indicateur de projet en alerte

Des filtres permettent d'analyser les résultats par :

- Pays
- Région
- Type de projet

---

### 📄 Page 3 – Analyse géographique

Analyse de la répartition des projets selon :

- les pays
- les régions
- le budget réel
- le nombre de projets
- le type de projet

Cette page permet d'identifier les zones nécessitant un suivi prioritaire.

---

### 📄 Page 4 – Documentation

Cette page regroupe :

- le Product Strategy Canvas ;
- les étapes de préparation des données ;
- le modèle relationnel ;
- la procédure de mise à jour du rapport ;
- les recommandations stratégiques issues de l'analyse.

---

## ⚙️ Préparation des données

Les données ont été préparées dans **Power Query**.

Les principales étapes sont :

- Import des fichiers Excel
- Vérification des en-têtes
- Contrôle des types de données
- Nettoyage des données
- Suppression des doublons
- Vérification des valeurs manquantes
- Création des colonnes calculées
- Création d'une clé composite (*Project_Phase*)
- Chargement des données dans Power BI

Toutes ces étapes sont enregistrées afin d'être automatiquement rejouées lors de chaque actualisation.

---

## 🧩 Modélisation des données

Le rapport repose sur un modèle relationnel composé de plusieurs tables reliées principalement grâce :

- au **Project ID**
- à la clé composite **Project_Phase**

Cette modélisation permet :

- d'éviter les doublons ;
- d'améliorer les performances ;
- de faciliter les calculs DAX ;
- de réaliser des analyses croisées entre plusieurs tables.

---

## 📐 Mesures DAX

Plusieurs mesures DAX ont été développées, notamment :

- Nombre de projets
- Budget prévu
- Budget réel
- Écart budget
- Écart budget (%)
- Durée prévue
- Durée réelle
- Écart durée
- Écart durée (%)
- Livrables prévus
- Livrables réels
- Écart livrables
- Nombre de projets en alerte

---

## 💡 Résultats

L'analyse met notamment en évidence :

- des dépassements de budget sur certains projets ;
- des retards de réalisation ;
- des écarts sur les livrables ;
- des différences de performance selon les pays et les régions.

Le tableau de bord permet ainsi de prioriser les actions et d'améliorer le pilotage du portefeuille de projets.

---

## 🔄 Mise à jour

Le rapport a été conçu pour être facilement actualisé.

Il suffit de :

1. Remplacer le fichier Excel source.
2. Ouvrir Power BI.
3. Cliquer sur **Actualiser**.
4. Les transformations Power Query sont automatiquement rejouées.
5. Les indicateurs et visualisations sont mis à jour.

---

## 🎓 Compétences développées

- Business Intelligence
- Data Visualisation
- Power BI
- Power Query
- DAX
- Modélisation relationnelle
- Nettoyage de données
- Storytelling Data
- Analyse décisionnelle
- Conception de tableaux de bord interactifs

---

