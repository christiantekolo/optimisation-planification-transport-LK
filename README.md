*English bellow*

# optimisation-planification-transport-LK
Optimisation de la planification des voyages d’une compagnie de transport au Togo
## Résumé du projet

Ce projet de data science vise à **identifier les trajets à risque** (retards, surcharge, insatisfaction client) pour une compagnie de transport routier au Togo, afin d’améliorer la planification des voyages et la qualité de service.

## Objectif

Prédire les situations d’insatisfaction client et fournir des **leviers d’action concrets** pour réduire les plaintes et améliorer l’expérience des passagers.

## Données

Données opérationnelles de trajets :

* distance, durée, retard
* prix du billet
* nombre de passagers et capacité du bus
* type de bus, état de la route
* consommation de carburant
* satisfaction client

---

## Approche

* Nettoyage et préparation des données
* Création de variables métier (surcharge, retard normalisé, efficacité carburant)
* Pipeline de prétraitement (scaling, encodage)
* Modélisation par **Random Forest**
* Reformulation de la cible en classification binaire (satisfait / non satisfait)
* Ajustement du seuil pour privilégier la détection des trajets à problème

---

## Résultats clés

* Le modèle détecte efficacement les **situations d’insatisfaction**
* L’objectif est la **prévention des problèmes**, pas uniquement l’optimisation du score
* Approche orientée décision plutôt que performance brute

---

## Facteurs les plus influents

* prix du billet
* retards et respect des horaires
* surcharge des bus
* efficacité de la consommation de carburant
* organisation du trajet (horaire, type de bus)

---

## Impact métier

* anticipation des trajets à risque
* meilleure gestion des capacités
* réduction des plaintes clients
* aide à la décision pour la planification des voyages

---

## Compétences démontrées

Analyse de données, feature engineering, pipelines Scikit-learn, machine learning supervisé, interprétation métier des résultats.

---

## Contenu du dépôt

* Notebook colab du projet
* Jeu de données 
* README

---

## Auteur

TEKOKO Ekoué Christian

*English*

# Transport Trip Planning Optimization – Data Science Project

## Project Overview

This data science project aims to **identify risky transport trips** (delays, overcrowding, customer dissatisfaction) for a road transport company in Togo, in order to improve trip planning and service quality.

---

## Objective

Predict situations that may lead to **customer dissatisfaction** and provide **actionable insights** to support operational decision-making.

---

## Data

Operational transport data including:

* trip distance, planned duration, and delays
* ticket price
* number of passengers and bus capacity
* bus type and road condition
* fuel consumption
* customer satisfaction

---

## Approach

* Data cleaning and preparation
* Feature engineering (bus occupancy rate, normalized delay, fuel efficiency indicators)
* Preprocessing pipeline (scaling and categorical encoding)
* Supervised machine learning using **Random Forest**
* Reformulation of the target into a **binary classification** (satisfied vs. not satisfied)
* Decision threshold adjustment to prioritize risk detection

---

## Key Results

* The model effectively identifies **high-risk trips** likely to generate customer dissatisfaction
* The focus is on **problem prevention**, not only on maximizing accuracy
* Results are aligned with real operational needs

---

## Most Influential Factors

* ticket price
* delays and schedule reliability
* bus overcrowding
* fuel efficiency
* overall trip organization (departure time, bus type)

---

## Business Impact

* early identification of problematic trips
* better capacity and schedule planning
* reduction in customer complaints
* decision support for transport managers

---

## Skills Demonstrated

Data analysis, feature engineering, Scikit-learn pipelines, supervised machine learning, model evaluation, business-oriented interpretation.

---

## Repository Content

* colab notebook with the full analysis
* Dataset (if included)
* README

---

## Author

Christian Tekolo

* écrire une **phrase d’accroche LinkedIn**,
* ou t’aider à **placer ce projet en premier sur ton CV**.
