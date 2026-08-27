# Zakaria Maachou

## Business Analyst | Analyse de données, Reporting & Aide à la décision

Je traduis les besoins métiers en KPI, analyses et reporting pour éclairer les décisions et améliorer la performance.

**Recherche : alternance Business Analyst / Data / BI / Reporting — dès septembre 2026 | Paris · Mobilité nationale**

[Portfolio](https://www.zakariamaachou.com/) · [LinkedIn](https://www.linkedin.com/in/zakaria-maachou/)

---

## Compétences

**Données & analyse** — SQL · Python · pandas · Excel
**Reporting & BI** — Tableau · Power BI · KPI · Reporting · Data Viz
**Qualité & modélisation** — Data Quality · ETL · dbt · DuckDB
**Métier** — CRM · Analyse de performance · Aide à la décision · Définition de KPI et de règles de gestion

---

## Expérience

**Data & BI Analyst** — My Job Glasses · Paris · Contrat d'apprentissage · 09/2025 - 08/2026
Fiabilisation de données SQL et ETL alimentant 20+ KPI clients, avec contrôles de cohérence avant diffusion aux équipes métiers. Conception, recette et documentation de 5+ dashboards Tableau pour le suivi récurrent de la performance.

**Assistant Marketing Digital & Data Reporting** — Biofa France · Strasbourg · Contrat d'apprentissage · 09/2024 - 08/2025
Analyse de 30+ campagnes digitales sur 4 canaux d'acquisition, avec suivi des principaux KPI de trafic, engagement et conversion. Centralisation de 5 sources marketing et harmonisation d'une quinzaine de KPI pour fiabiliser le reporting.

---

## Formation

| Période | Formation | École |
|---|---|---|
| 09/2025 - 09/2027 | MSc Data Management & AI for Business | INSEEC MSc - Paris |
| 09/2024 - 09/2025 | M1 Digital Business & Marketing - Programme Grande École | EBS Paris - European Business School |
| 09/2020 - 07/2023 | Licence Économie et gestion - Analyse économique | Université Paris-Panthéon-Assas |

---

## Projets

Quatre projets personnels menés de bout en bout, structurés de la même façon : problème métier, méthode, sorties, technologies.
Lecture guidée et détail complet sur le [portfolio](https://www.zakariamaachou.com/).

### 1. RenewalOS — Fiabilité du revenu B2B & priorisation Customer Success

**Problème métier** — Les équipes B2B pilotent l'ARR, le churn et le renouvellement à partir de sources qui ne concordent pas toujours. Comment savoir si les KPI de revenu sont fiables *avant* que le Customer Success priorise ses comptes ?

**Méthode** — Chargement des sources dans un entrepôt DuckDB modélisé avec dbt, application de contrôles qualité et de réconciliation du revenu en amont de tout reporting, puis diagnostic explicable de santé des comptes et priorisation sous contrainte de capacité CSM.

**Sorties** — Périmètre de 7 sources sur 24 mois et 750 comptes · 14 scénarios d'incidents qualité détectés · 26 modèles dbt (staging, intermediate, qualité, marts) · réconciliation ARR · contrôle qualité bloquant en amont du reporting · Control Tower Streamlit.

**Technologies** — SQL · dbt · DuckDB · Python · Streamlit · OR-Tools

[Dépôt](https://github.com/zakaria9622/renewalos-b2b-revenue-quality-engine) · [Démo](https://renewalos-zakaria.streamlit.app/)

---

### 2. Funnel e-commerce & leviers de conversion

**Problème métier** — Où les utilisateurs abandonnent-ils avant l'achat, et faut-il agir sur la page produit ou sur le paiement ?

**Méthode** — Funnel utilisateur strictement chronologique en SQL (première vue → premier panier après la vue → premier achat après le panier), comptage d'utilisateurs uniques par étape, contrôles de qualité, puis dashboard Tableau destiné aux équipes métiers.

**Sorties** — 3 022 130 visiteurs · 336 718 utilisateurs avec panier · 196 474 acheteurs · taux vue → panier 11,14 % · taux panier → achat 58,35 % · conversion globale 6,50 %. Le principal point de friction se situe entre la vue produit et l'ajout au panier, et non au paiement.

**Technologies** — SQL · DuckDB · Python · pandas · Tableau

[Dépôt](https://github.com/zakaria9622/funnel-analysis-project)

---

### 3. Segmentation RFM & recommandations CRM

**Problème métier** — Quels clients le CRM doit-il protéger, réactiver ou déprioriser, et sur quels critères objectifs ?

**Méthode** — Agrégation au niveau client, scoring RFM par quintiles (récence, fréquence, montant), affectation de segments mutuellement exclusifs, puis règles de priorisation fondées sur l'économie de chaque segment.

**Sorties** — 5 000 clients · 45 356 commandes · segments VIP, Loyaux, À risque et Perdus · les VIP représentent 27,9 % des clients et 75,4 % du chiffre d'affaires, les Perdus 23,62 % des clients et 2,95 % du CA. Priorisation CRM : protéger les VIP, réactiver les À risque avant bascule, ne pas surinvestir sur les Perdus.

**Technologies** — Python · pandas

[Dépôt](https://github.com/zakaria9622/customer-segmentation-rfm)

---

### 4. Rentabilité e-commerce & fuites de marge

**Problème métier** — Où la marge se dégrade-t-elle, et quelles catégories, régions ou politiques de remise en sont responsables ?

**Méthode** — Couche analytique DuckDB au niveau commande, calcul du chiffre d'affaires, des coûts, de la marge et des remises par segment, identification des commandes à perte et des couples catégorie × région les plus fragiles, restitution Tableau.

**Sorties** — 12 000 commandes · CA 2 054 589 € · marge 214 041 € · taux de marge 10,42 % · remise moyenne 17,39 % · 16,01 % de commandes à perte. La fuite de marge se concentre sur le couple Électronique / UE, et les remises élevées dégradent systématiquement la marge.

**Technologies** — SQL · DuckDB · Python · pandas · Tableau

[Dépôt](https://github.com/zakaria9622/ecommerce-profit-leak-analysis)


## Langues

Français C1 · Anglais C1

---
*Les quatre projets ci-dessus sont des projets personnels réalisés à des fins de démonstration analytique. Le périmètre et les limites de chaque jeu de données sont documentés dans le dépôt correspondan
