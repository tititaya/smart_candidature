[![CI](https://github.com/tititaya/candidature_intelligente/actions/workflows/ci.yml/badge.svg)](https://github.com/tititaya/candidature_intelligente/actions)


# 🤖 smart_candidature

Assistant intelligent pour candidatures spontanées automatisées 📬  
Conçu avec Python, IA (Groq), Streamlit, scraping, et base de données locale ou distante.

## 🧠 Objectif
Automatiser tout le processus de candidature :
- Rechercher des entreprises
- Identifier les bons contacts (RH, tech, etc.)
- Générer des lettres personnalisées avec IA
- Envoyer les mails automatiquement
- Suivre les réponses et relancer si besoin
- Visualiser toutes les stats depuis un dashboard web

## 📦 Fonctionnalités
- Scraping de Pages Jaunes, Welcome to the Jungle, Data.gouv
- Recherche de profils sur LinkedIn
- Deviner les formats d’email pro
- Génération de lettres de motivation avec Groq (LLaMA 3)
- Envoi d’emails + relances planifiées
- Dashboard Streamlit accessible partout
- Notifications Telegram, rapports PDF, sauvegardes
- CI/CD avec GitHub Actions + déploiement Docker possible

## ⚙️ Tech stack
Python, SQLite/PostgreSQL, Streamlit, Selenium, requests, dotenv, schedule, Docker, GitHub Actions

## 🚀 Lancer le projet
```bash
# Cloner le repo
git clone git@github.com:tititaya/smart_candidature.git
cd smart_candidature

conda create -n smart_candidature python=3.11
conda activate smart_candidature

# Installer les dépendances
pip install -r requirements.txt

# Lancer le dashboard
streamlit run interface/dashboard.py
```

## 📍 Roadmap
## 📂 Structure du projet
Voir [`STRUCTURE.md`](https://github.com/tititaya/smart_candidature/blob/main/STRUCTURE.md) pour l’arborescence complète.

