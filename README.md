# MRM-Oversight : Model Risk Management Dashboard (2LoD)

🚀 [Live dashboard](#) *(Pensez à remplacer le # par votre lien Streamlit final)*

## 🛡️ Overview

Streamlit web application prototype for Model Risk Management (2nd Line of Defence), designed to monitor a portfolio of quantitative risk models (IFRS 9, IRB, ALM, Market Risk). It features performance drift tracking (PSI/AUC), regulatory compliance monitoring, and an NLP-based assistant for automated validation report analysis.

## 📊 Modules Included

* **Vue d'ensemble :** KPIs consolidés du portefeuille (45+ modèles supervisés), suivi du taux de conformité global et alertes rouges de performance.
* **Matrice de Risque (Stabilité vs Pouvoir Discriminant) :** Scatter plot interactif identifiant les modèles franchissant les seuils internes ou réglementaires (ex: PSI > 0.25, AUC < 0.65).
* **Suivi Temporel (Drift Analysis) :** Visualisation détaillée de la dégradation des performances d'un modèle spécifique sous surveillance sur un horizon de 12 mois.
* **Assistant Audit IA (NLP) :** Module de simulation LLM permettant d'extraire automatiquement les faiblesses méthodologiques (*Findings*) et de synthétiser les avis du comité de validation.
