# 📊 Étude exploratoire sur les habitudes de consommation des étudiants à Dakar

Ce projet a pour objectif d'analyser les résultats d'une enquête menée auprès de 500 étudiants vivant dans la région de Dakar. L'étude vise à comprendre leurs comportements de consommation, leur niveau de satisfaction vis-à-vis des services existants, et à évaluer leur intérêt pour une nouvelle offre.

## 🎯 Objectifs de l'étude

- Identifier les profils sociodémographiques dominants
- Analyser les habitudes d’achat et la satisfaction
- Déterminer les leviers d’adhésion à un nouveau service
- Fournir des recommandations opérationnelles basées sur les données

## 🧰 Données utilisées

Le fichier utilisé est **Donnees_etude_marche.xlsx**, contenant :
- Données sociodémographiques (sexe, âge, commune)
- Données de consommation (fréquence d’achat, dépenses, produits connus)
- Données de perception (qualité perçue, satisfaction, intérêt pour un nouveau service)
- Variables d’opinion (importance du prix, qualité, image, etc.)
- Commentaires libres des répondants

## 🧪 Méthodologie

L'analyse s'est déroulée en deux phases :

### 1. Analyse univariée
- Statistiques descriptives pour chaque variable
- Visualisations (histogrammes, boxplots, diagrammes circulaires)
- Résumés des commentaires qualitatifs

### 2. Analyse bivariée
- Tests de dépendance (khi², Student, ANOVA, corrélations)
- Comparaisons croisées entre variables sociodémographiques et comportementales
- Identification de corrélations entre satisfaction et intérêt pour le nouveau service

## 📈 Outils utilisés

- Python (pandas, seaborn, matplotlib, scipy, statsmodels)
- Jupyter Notebook
- Excel (exploration initiale)
- Tableau ou Looker Studio pour les dashboards

## 🧠 Résultats clés

- Les étudiants les plus satisfaits sont ceux qui perçoivent une meilleure disponibilité et qualité du service.
- Le niveau de connaissance des produits influence fortement la fréquence d’achat.
- Le levier principal d’adhésion est le **rapport qualité/prix**, suivi de la **disponibilité**.
- Les supports d’information préférés varient selon la commune et l’âge.

## 📎 Organisation du projet
- `data/` : Données brutes de l'enquête
- `notebooks/` : Notebook Jupyter d'analyse exploratoire
- `scripts/` : Scripts Python pour le traitement des données
- `rapport/` : Rapport final
- `README.md` : Présentation du projet

## 👨‍💻 Auteur

Projet réalisé par Cheikh Abdou MBACKE, étudiant en Science du Management et de la Décision – PGE 2 (CESAG)  
Juin 2025
