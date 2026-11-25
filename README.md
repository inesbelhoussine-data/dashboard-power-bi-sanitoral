
# Sanitoral — Executive Reporting & Project Performance Analytics

## Executive Summary

Conception d'une solution de Business Intelligence destinée
à accompagner la direction générale, les directions régionales
et les directions nationales dans le pilotage d'un portefeuille
international de 104 projets IT et Marketing.

Cette étude de cas réalisée dans le cadre de ma formation
Data Analyst chez OpenClassrooms vise à transformer des données
financières et opérationnelles en informations décisionnelles
et recommandations stratégiques.

## Key Business Findings

| Indicateur | Résultat |
|---|---:|
| Projets analysés | 104 |
| Projets IT | 52 |
| Projets Marketing | 52 |
| Régions internationales | 4 |
| Projets en alerte | 76 |
| Taux de projets en alerte | 73,1 % |
| Budget prévisionnel | 56 108 000 |
| Budget réel | 62 035 400 |
| Dépassement budgétaire | 5 927 400 |
| Écart budgétaire | +10,56 % |
| Écart de durée cumulée | -13,43 % |
| Écart de livrables | Environ -10,3 % |

## Business Challenge

Sanitoral dispose de nombreuses données relatives à ses
projets internationaux, mais ne bénéficie pas d'une vision
centralisée permettant d'identifier rapidement les écarts
de performance et de prioriser les interventions.

Les enjeux sont les suivants :

- Maîtriser les dépenses et les dépassements budgétaires.
- Identifier les projets présentant des risques.
- Suivre le respect des délais et des engagements.
- Évaluer la réalisation des livrables.
- Faciliter les décisions de poursuite ou d'arrêt des projets.
- Accompagner les directions dans leurs actions correctives.

## Stakeholders & Decision Support

### Direction générale

- Pilotage global du portefeuille de projets.
- Identification des écarts significatifs.
- Arbitrage concernant la poursuite ou l'arrêt des projets.

### Directions régionales

- Analyse comparative des performances.
- Identification des projets nécessitant une intervention.
- Coordination avec les directions nationales.

### Directions nationales

- Analyse détaillée des projets.
- Identification des causes de dérive.
- Mise en œuvre de mesures correctives.

## Analytical Approach

### 1. Data Preparation — Power Query

- Importation des différentes sources de données.
- Nettoyage et transformation des données.
- Harmonisation des types de variables.
- Création d'une clé composite Project_Phase.
- Préparation des données pour le reporting.

### 2. Data Modeling

Construction d'un modèle relationnel composé de sept tables
de données :

- Actual_Costs
- Actual_Deliverable
- Actual_Duration
- Country_Profiles
- Project type
- Projects_Locations
- Projects_plans

Rapprochement des données réelles et prévisionnelles
à l'échelle des projets et de leurs phases.

### 3. KPI Development — DAX

Création d'indicateurs permettant de mesurer :

- Les coûts réels et prévisionnels.
- Les écarts budgétaires.
- Les durées réelles et prévisionnelles.
- Les écarts de durée.
- Les livrables réalisés et attendus.
- Le nombre de projets en alerte.

Le seuil d'alerte défini dans le cahier des charges
est fixé à 15 % d'écart.

### 4. Business Intelligence — Power BI

Conception d'un reporting interactif permettant :

- Le suivi global du portefeuille.
- L'analyse détaillée des projets.
- L'analyse géographique des investissements.
- Le filtrage par région, pays et catégorie de projet.

## Business Findings

### Financial Performance

Le portefeuille présente un budget réel de 62 035 400
pour un budget prévisionnel de 56 108 000.

Le dépassement global atteint 5 927 400,
soit environ 10,56 % du budget initial.

### Project Risk Management

76 projets sur 104 sont identifiés comme étant en alerte,
soit environ 73,1 % du portefeuille.

Cette proportion souligne la nécessité de prioriser
les interventions et d'investiguer les causes des écarts.

### Operational Performance

Les durées cumulées sont inférieures de 13,43 %
aux prévisions.

Cependant, environ 900 livrables de moins que prévu
sont comptabilisés.

Ces résultats nécessitent une analyse complémentaire
afin de déterminer si les durées réduites correspondent
à des gains d'efficacité, des changements de périmètre
ou des livrables non réalisés.

### Project-Level Analysis

Le projet Marketing numéro 4, situé en Égypte,
présente notamment :

- Budget prévu : 750 000
- Budget réel : 981 700
- Surcoût : 231 700
- Dépassement budgétaire : environ 31 %
- Dépassement de durée : environ 95 %

Ce projet constitue un exemple de situation nécessitant
une revue financière et opérationnelle prioritaire.

### Geographic Analysis

Les budgets réels les plus élevés parmi les pays
visibles dans le reporting concernent notamment :

- Norvège : 3,4 millions
- Allemagne : 3,3 millions
- Belgique : 2,8 millions

Ces résultats permettent d'identifier les zones
concentrant des investissements importants.

## Strategic Recommendations

1. Prioriser les projets cumulant plusieurs écarts
   défavorables.

2. Analyser les causes des dépassements budgétaires.

3. Renforcer le suivi des engagements et des livrables.

4. Mettre en place des revues régulières de performance
   avec les directions régionales et nationales.

5. Adapter l'allocation des ressources en fonction
   des risques et des priorités stratégiques.

6. Vérifier la pertinence des seuils d'alerte
   et distinguer les écarts favorables des écarts
   défavorables.

7. Approfondir l'analyse des projets présentant
   simultanément des surcoûts et des retards.

## Business Value

La solution développée fournit un support décisionnel
permettant de :

- Centraliser les informations financières et opérationnelles.
- Améliorer la visibilité sur les performances des projets.
- Identifier les situations nécessitant une intervention.
- Faciliter les arbitrages budgétaires.
- Soutenir la coordination entre les niveaux de direction.

Les bénéfices présentés correspondent aux usages
potentiels de la solution et non à des gains financiers
mesurés après déploiement.

## Technical Stack

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Data Visualization
- KPI Monitoring
- Financial Analysis
- Executive Reporting

## Project Context

Étude de cas professionnalisante réalisée dans le cadre
de la certification Data Analyst OpenClassrooms.

## Author

Ines Belhoussine

Business Data Analyst | Business Intelligence
& Strategic Decision Support
