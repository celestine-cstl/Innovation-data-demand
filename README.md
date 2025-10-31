# Analyse de la performance d’innovation & demande de compétences

**Projet R : nettoyer les données “brevets” et “offres d’emploi”, extraire les codes technologiques (IPC-4) et apparier les entreprises pour étudier le lien innovation et compétences/salaires (France, 2010–2020).**

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge\&logo=r\&logoColor=white)
![dplyr](https://img.shields.io/badge/dplyr-7DBA3B?style=for-the-badge)
![stringr](https://img.shields.io/badge/stringr-4E9BCD?style=for-the-badge)
![tidyr](https://img.shields.io/badge/tidyr-1F72B5?style=for-the-badge)

> Travail fait en **R** (packages **dplyr**, **stringr**, **tidyr**) avec des fonctions simples pour **lire**, **nettoyer**, **standardiser** et **joindre** les données

<br>

## 🎯 Objectifs

* Les entreprises les plus innovantes proposent-elles des **salaires** plus élevés ?
* L’innovation s’accompagne-t-elle d’une demande accrue en **data science / machine learning** ?
* Quels **secteurs** ou **domaines technologiques (IPC)** lient le plus fortement innovation et compétences recherchées ?

<br>

## 🛠️ Compétences mobilisées
- **Data engineering** : ingestion multi-formats, transformation des tables, jointures pour construire une base unique.
- **Qualité des données** : nettoyage, normalisation des champs (types, unités), contrôles simples de cohérence.
- **Traitement de texte** : standardisation de chaînes (majuscules, accents, formes juridiques), petits mappings/regex pour aligner noms d’entreprises et compétences.
- **Analyse descriptive** : agrégations par entreprise/secteur/technologie, indicateurs synthétiques (comptages, moyennes), comparaisons de groupes


<br>

## 📌 Résultats clés

**Les entreprises fortement brevettantes présentent plus souvent une demande structurée en compétences data/ML** et des niveaux de **salaires généralement plus élevés** dans leurs offres techniques. Certains domaines technologiques (IPC) et secteurs se distinguent par une co-présence marquée de l’activité d’innovation et de besoins en compétences analytiques. L’appariement met aussi en évidence des entreprises avec innovation active mais peu d’offres visibles (ou l’inverse), utile pour repérer des décalages entre R&D et recrutement
