# 🏥 Dashboard de Performance Hospitalière 

## 📋 Présentation du Projet

Ce projet présente un tableau de bord analytique conçu pour le suivi de la performance et de la qualité des soins au sein d'un établissement hospitalier (**Apollo Hospitals**).

L'objectif est de fournir une vue d'ensemble mensuelle aux décideurs (cadres de santé, directeurs d'établissement) pour optimiser la gestion des lits, des ressources humaines et le suivi des pathologies.

> **Note :** Les données utilisées pour ce dashboard sont entièrement **fictives** et générées à des fins de démonstration.

---

## 📊 Indicateurs Clés (KPIs)

Le dashboard se concentre sur quatre axes majeurs :

* **Flux d'Entrées :** Volume total des admissions sur le mois (500 entrées).
* **Durée Moyenne de Séjour (DMS) :** Indicateur d'efficience opérationnelle (7,36 jours).
* **Taux de recours aux soins critiques :** Proportion de patients nécessitant une prise en charge en réanimation (51,80 %).
* **Activité Soignante :** Volume total des interventions réalisées (841 actes).

---

## 🔍 Analyses Détaillées

### 1. Gestion de la Capacité (Hospitalisation)

* **Répartition de la charge :** Comparaison entre le service de Réanimation (48,2 %) et le Service Conventionnel (51,8 %).
* **Mix des Procédures :** Segmentation des actes médicaux (Appendicectomie, Bilan Sanguin, IRM, Radio Thorax) par type d'unité.

### 2. Profil Épidémiologique

* **Top 4 des Diagnostics :** Identification des pathologies prédominantes (Fracture, Diabète, Appendicite, Pneumonie) pour adapter les stocks et les compétences.

### 3. Efficience Ressources vs Séjour

* **Corrélation Staff/DMS :** Un graphique à bulles mettant en évidence la gestion médico-économique des cas complexes, comparant l'allocation des ressources à la durée d'hospitalisation par unité.

---

## 🛠️ Technologies Utilisées

* **Outil de Visualisation :** Power BI
* **Design :** UI/UX orienté "Clean Health Data"
* **Données :** Dataset fictif (CSV)

---

## 🚀 Comment utiliser ce Dashboard ?

1. Le menu latéral gauche permet de filtrer les données par **Type d'Hospitalisation** (Réanimation vs Conventionnel).
2. Des menus déroulants permettent d'affiner l'analyse par **Diagnostic Médical** ou **Type d'Intervention**.
3. Les graphiques temporels en haut permettent d'identifier les pics d'activité sur la période du 6 au 27 octobre.

---

## 💡 Perspectives d'Amélioration

* Intégration de données comparatives (N vs N-1).
* Ajout d'un score de satisfaction patient (Net Promoter Score).
* Automatisation des flux de données via API.
