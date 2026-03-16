# 🏥 Analyse des Temps d'Attente aux Urgences (Projet_Urgence)

## 📋 Contexte et Problématique
Ce projet porte sur l'analyse massive des données hospitalières pour l'année **2024**. L'objectif principal est d'identifier les facteurs déterminants des délais de prise en charge afin de proposer des solutions concrètes pour **réduire les temps d'attente aux urgences**.

**Les défis adressés :**
* Analyse de plus de **1 020 000 visites**.
* Traitement de **12 fichiers mensuels** consolidés.
* Identification des périodes critiques et des établissements les plus affectés.

## 🛠️ Stack Technique
* **Langage :** Python 🐍
* **Bibliothèques :** Pandas (Traitement de données), NumPy, Matplotlib/Seaborn (Visualisation)
* **Outils :** Jupyter Notebook, Git/GitHub (Version Control)
* **Environnement :** WSL (Ubuntu sur Windows)

## 🚀 Fonctionnalités Clés du Notebook
Le projet suit une méthodologie rigoureuse de Data Science :
1. **Ingestion & Nettoyage :** Consolidation des fichiers CSV et gestion des types (conversion datetime, numeric).
2. **Contrôle Qualité :** Détection automatique des anomalies (dates d'expédition incohérentes, erreurs de calcul de montants, doublons).
3. **Pipeline de Traitement :** Suppression des valeurs manquantes critiques et normalisation des colonnes.
4. **Analyse Exploratoire (EDA) :** Visualisation des indicateurs clés de performance (KPI) pour aider à la prise de décision.

## 📂 Structure du Dépôt
```bash
.
├── Data/                   # Dossier contenant les fichiers de données sources
├── Untitled (9).ipynb      # Notebook principal de traitement et analyse
└── README.md               # Documentation du projet
