# Comp-tence-C2.4-Produire-une-preuve-de-concept-fonctionnelle


🚀 Analyse des Avis Clients avec NLP & Dashboard Interactif

📌 Description du Projet

Ce projet permet d'extraire, d'analyser et de visualiser des avis clients provenant de différentes plateformes (Google Reviews, Trustpilot, Apple App Store). L'objectif est d'utiliser le Traitement du Langage Naturel (NLP) pour détecter les tendances de satisfaction, classifier les avis en positifs, neutres ou négatifs, et fournir un tableau de bord interactif pour visualiser les résultats.

🏗️ Architecture de la Solution

1️⃣ Scraping des avis clients 📤 (Scrapy, Selenium)2️⃣ Analyse des sentiments 💡 (GPT, Gemini, Mistral)3️⃣ Calcul des KPI & Stockage 🛠️ (Pandas, MongoDB)4️⃣ Visualisation des résultats 📊 (Streamlit, Matplotlib)

🎯 Fonctionnalités

✅ Extraction automatique des avis clients 📥✅ Analyse des sentiments (Positif, Neutre, Négatif) 🔍✅ Calcul des KPI 📊 (moyenne des avis, taux de satisfaction)✅ Visualisation des résultats sur un dashboard interactif✅ Export des données en format exploitable (CSV, JSON)

🛠️ Technologies Utilisées

Langage : Python 🐍

Scraping : Scrapy, Selenium 🔍

NLP : Transformers (HuggingFace), GPT, Gemini, Mistral 🤖

Stockage : MongoDB (ou CSV) 💾

Dashboard : Streamlit, Matplotlib 📊

🔧 Installation et Exécution

1️⃣ Installation des dépendances

Exécutez la commande suivante pour installer les bibliothèques requises :

pip install -r requirements.txt

2️⃣ Exécuter le Scraping des Avis

python scraping.py

3️⃣ Lancer l'Analyse NLP

python nlp_analysis.py

4️⃣ Démarrer le Dashboard Streamlit

streamlit run dashboard.py

Une URL sera générée pour accéder au dashboard interactif.

📂 Structure du Projet

📁 Projet_Avis_Clients
│── 📂 data                 # Données brutes et transformées
│── 📂 models               # Modèles NLP pré-entraînés
│── 📂 src                  # Code source
│   │── scraping.py        # Script de scraping des avis
│   │── nlp_analysis.py    # Analyse des sentiments avec NLP
│   │── dashboard.py       # Dashboard interactif avec Streamlit
│── requirements.txt        # Dépendances du projet
│── README.md               # Documentation du projet

📊 Résultats et Visualisation

Le projet affiche un tableau de bord interactif avec :

La moyenne des avis clients

Un graphique circulaire montrant la répartition des avis (Positif, Neutre, Négatif)

Une liste des avis clients analysés

Exemple de visualisation :


🚀 Améliorations Futures

Optimisation du scraping pour une exécution plus rapide

Ajout de nouvelles sources d'avis clients

Déploiement d'une API REST pour l'analyse NLP en temps réel

Automatisation complète de l'analyse et génération de rapports

