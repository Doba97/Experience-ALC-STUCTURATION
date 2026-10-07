# Expérience professionnelle : Africa Link Capital (ALC)

> **Durée :** environ 1 an et 3 mois (6 mois de stage + 3 mois de perfectionnement + 6 mois à temps partiel)
> **Environnement :** Département Structuration / Data
> **Domaines :** titrisation, analyse de données financières et bancaires, Business Intelligence, Machine Learning, reporting, qualité des données

## 1. Présentation

Mon expérience au sein de **Africa Link Capital (ALC)** s'est déroulée sur une période d'environ **1 an et 3 mois**, composée de :

- **6 mois de stage**
- **3 mois de perfectionnement**
- **6 mois à temps partiel**

Elle m'a permis de travailler sur des problématiques concrètes à la croisée de la **finance, de la titrisation, de l'analyse de données, de la Business Intelligence et du Machine Learning**.

Les missions réalisées se regroupent autour de deux grands axes :

1. **Analyse de données financières et bancaires dans le cadre d'opérations de titrisation**
2. **Analyse et valorisation des données du Programme Électricité Pour Tous (PEPT)**

L'objectif global était de transformer des données brutes et volumineuses en **indicateurs fiables, analyses exploitables, outils de pilotage et modèles prédictifs**.

---

## 2. Analyse de données bancaires et opérations de titrisation

Une partie importante de mon expérience a porté sur l'exploitation et l'analyse de données provenant d'établissements bancaires dans le cadre d'opérations de titrisation.

Les travaux ont notamment concerné des données issues de :

- **Bridge Bank**
- **Orabank**
- **Ecobank**

### Travaux réalisés

- Collecte et exploration de données bancaires
- Nettoyage et préparation des bases de données
- Analyse des caractéristiques des créances
- Contrôle de la cohérence et de la qualité des données
- Analyse des portefeuilles de créances
- Calcul et analyse d'indicateurs financiers
- Préparation des données destinées aux analyses de titrisation
- Analyse de la structure et de la qualité des portefeuilles
- Contribution à la préparation de supports de présentation
- Réalisation de **teasers** dans le cadre des opérations de titrisation

---

## 3. Titrisation

Cette expérience m'a permis de mieux comprendre le processus de **titrisation de créances** et le rôle de la donnée dans la préparation et l'analyse d'une opération.

La chaîne de travail peut être représentée ainsi :

```text
Données bancaires
       ↓
Collecte et contrôle
       ↓
Nettoyage / Préparation
       ↓
Analyse du portefeuille
       ↓
Indicateurs financiers
       ↓
Analyse de la qualité des créances
       ↓
Structuration de l'opération
       ↓
Teaser / Présentation
       ↓
Investisseurs / Décision
```

---

## 4. Projet PEPT : Programme Électricité Pour Tous

### Contexte

Le PEPT est un programme visant à faciliter l'accès à l'électricité aux populations économiquement faibles.

Dans le cadre de son suivi, les données de la **CIE** ont été exploitées afin d'analyser notamment :

- les branchements et les compteurs ;
- la consommation électrique et les achats d'énergie ;
- les règlements, les redevances et les comportements de paiement ;
- les performances par zone, région et direction régionale.

### Travaux réalisés

- Collecte et intégration de données provenant de plusieurs sources
- Nettoyage et transformation de données volumineuses
- Contrôle de la qualité et recherche d'incohérences
- Analyse des branchements, des compteurs et de la consommation
- Analyse des redevances, du recouvrement et des comportements de paiement
- Analyses par zone, région, direction régionale, offre et période
- Production de KPI et de reportings
- Restitution des résultats sous forme de tableaux de bord et de présentations

---

## 5. Automatisation du reporting PEPT

Un travail important a consisté à **automatiser la production des rapports PEPT** afin de réduire les traitements manuels et de rendre le processus plus reproductible.

- Prétraitement automatique des fichiers mensuels
- Transformation et contrôle des données
- Calcul automatique des indicateurs
- Génération de tableaux et de graphiques
- Production automatisée de plusieurs parties du reporting
- Préparation de présentations PowerPoint
- Mise en place de workflows reproductibles

**Outils :** Python · R · SQL · Q/KDB+ · Excel · Power BI · PowerPoint · Streamlit

---

## 6. Dashboards et Business Intelligence

Participation à la conception de tableaux de bord **Power BI** permettant de suivre les performances du programme.

- Préparation des données
- Création de mesures et d'indicateurs
- Mise en forme des KPI
- Analyses temporelle et géographique
- Analyses par direction régionale, par région et par offre
- Création de visualisations destinées au pilotage

**Objectif :** mettre à disposition une information synthétique et exploitable pour suivre les performances, identifier les anomalies, analyser les tendances et faciliter la prise de décision.

---

## 7. Modèle prédictif du paiement des redevances

### Objectif

Développer un outil permettant d'anticiper le comportement de paiement des bénéficiaires PEPT, en estimant pour chaque client la **probabilité de paiement de sa redevance au mois M+1**.

### Approche

La modélisation a été réalisée selon la démarche **CRISP-DM** :

1. Compréhension du besoin métier
2. Compréhension des données
3. Préparation des données
4. Modélisation
5. Évaluation
6. Préparation de la mise à disposition opérationnelle

### Modèles et évaluation

Trois modèles ont été étudiés : **régression logistique**, **Random Forest** et **XGBoost**, comparés à l'aide de l'accuracy, de la precision, du recall, du F1-score et de l'AUC-ROC.

**XGBoost** a obtenu les meilleures performances :

| Métrique | Résultat |
|---|---:|
| Accuracy | 82,7 % |
| F1-score | 0,795 |
| AUC-ROC | 0,905 |

### Exploitation métier

- Segmenter les clients selon leur niveau de risque
- Identifier les clients les plus susceptibles de ne pas payer
- Prioriser les actions de relance
- Faciliter l'allocation des ressources de recouvrement

Un **seuil de décision de 0,35** a été retenu dans le cadre du dispositif étudié.

---

## 8. Mise à disposition du modèle

La réflexion ne s'est pas limitée à l'entraînement du modèle. **Architecture envisagée :**

```text
Données → Modèle ML → API → Application / Tableau de bord → Équipes opérationnelles
```

**Composants :** Python, Joblib / Pickle, FastAPI / Flask / Django, Docker, API REST, dashboard, cloud.

L'objectif est de permettre aux utilisateurs métier d'exploiter les prédictions sans manipuler directement le code Python.

---

## 9. Qualité et contrôle des données

La fiabilité des données a été une préoccupation constante, aussi bien sur les portefeuilles bancaires que sur les données du PEPT.

- Détection de valeurs manquantes
- Normalisation des données
- Contrôle des modalités
- Vérification des incohérences
- Harmonisation de données provenant de plusieurs sources
- Vérification de la cohérence des indicateurs
- Analyse des écarts entre différentes sources

Dans le cadre du PEPT, des travaux de rapprochement ont notamment permis de clarifier certaines règles métier, dont la définition du **mois de branchement**, ainsi que certains écarts observés dans les données de redevance et de paiement.

---

## 10. Technologies et outils

| Catégorie | Outils |
|---|---|
| **Data & programmation** | Python, R, SQL, Q/KDB+ |
| **Business Intelligence** | Power BI, Excel, PowerPoint, Streamlit |
| **Machine Learning** | Régression logistique, Random Forest, XGBoost, classification, scoring, évaluation de modèles |
| **Data Engineering** | ETL / prétraitement, transformation de données, traitement de volumes importants, workflows automatisés, réflexion Data Lake / Data Warehouse |
| **Développement / déploiement** | Git, GitLab, API, FastAPI / Flask / Django, Docker, Cloud |
| **Cartographie** | Données géographiques, cartographies des régions et directions, QGIS |

---

## 11. Git et collaboration

Les développements et scripts ont été organisés avec **Git/GitLab** : versionnement du code, organisation des scripts, collaboration, maintenance des traitements et structuration des projets.

---

## 12. Réflexion sur l'évolution Data / Digital d'ALC

Une réflexion a également été menée autour de la transformation d'ALC Structuration vers une organisation davantage orientée **Data, Développement & Digital/Technologies**.

```text
Finance / Titrisation
        ↓
Collecte des données
        ↓
Data Engineering / ETL
        ↓
Qualité & Gouvernance
        ↓
Data Warehouse / Data Lake
        ↓
Data Analysis / BI
        ↓
Data Science / Machine Learning
        ↓
API / Applications métier
        ↓
Power BI / Reporting
        ↓
Aide à la décision
```
