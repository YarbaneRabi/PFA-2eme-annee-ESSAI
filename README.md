# 🧮 Tarification des Sinistres en Assurance Automobile

Projet de fin d’année (PFA) – 2ᵉ année cycle ingénieur  
**Spécialité : Statistique et Analyse de Données**  
**École Supérieure de la Statistique et de l’Analyse de l’Information (ESSAI)**

## 📌 Objectif
Développer un système de tarification prédictive permettant d’estimer :
- Le **nombre de sinistres** attendus par assuré (fréquence),
- Le **montant moyen** des sinistres (coût moyen),
- Et le **coût total** attendu à travers un **modèle coût-fréquence**.

## 🛠️ Méthodologie

### 1. **Analyse exploratoire**
- Statistiques descriptives univariées et bivariées
- Cartographie des sinistres (analyse spatiale)
- Visualisations interactives via **R Shiny**

### 2. **Modélisation statistique**
- Régression Poisson / Binomiale négative
- Modèles **GLM** avec tests d’ajustement
- Approches **Zero-Inflated** pour gérer les zéros excessifs

### 3. **Approche machine learning**
- **XGBoost** appliqué sur fréquence, coût, et coût total
- Optimisation avec **RandomizedSearchCV** et **Optuna**
- Analyse de l’importance des variables
- Interprétation locale avec **SHAP**

### 4. **Visualisation & interface**
- Dashboard interactif sous **R Shiny** : exploration des données et diagnostics
- Déploiement d’un modèle final via **Streamlit**, hébergé sur **Hugging Face Spaces**

## 🔧 Technologies
- `Python` : scikit-learn, xgboost, shap, optuna, pandas
- `R` : shiny, ggplot2, sf (cartographie)
- `Streamlit` pour l’interface web
- `Hugging Face` pour l’hébergement



