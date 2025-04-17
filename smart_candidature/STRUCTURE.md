# 📁 Structure du Projet – smart_candidature

Dernière mise à jour : 2025-04-17

## Racine du projet
```
smart_candidature/
│
├── main.py                          # Point d'entrée du projet (scheduler ou debug)
├── config/
│   ├── config.py                    # Configurations globales
│   └── secrets.env                  # Clés API (non versionné)
├── interface/
│   ├── cli.py                       # Menu en ligne de commande
│   ├── dashboard.py                 # Interface web Streamlit
│   └── api.py                       # (optionnel) API REST
├── scheduler/
│   └── tasks.py                     # Tâches automatiques : scraping, relance, envoi
├── db/
│   ├── manager.py                   # Accès à la base
│   └── schema.sql                   # Création des tables
├── entreprise_scraper/
│   ├── base.py
│   ├── pagesjaunes.py
│   ├── welcome_to_jungle.py
│   ├── data_gouv.py
│   └── email_scraper.py
├── linkedin/
│   ├── search.py
│   ├── email_guesser.py
│   └── enrich_profiles.py
├── generator/
│   ├── prompt_builder.py
│   ├── letter_generator_ai.py
│   └── simulator.py
├── sender/
│   ├── email_sender.py
│   └── relancer.py
├── monitoring/
│   ├── logs.py
│   └── report.py
├── backup/
│   ├── backup.py
│   └── drive_sync.py
├── notifications/
│   └── telegram_bot.py
├── templates/
│   └── lettre_template.txt
├── data/
│   ├── candidature.db
│   ├── lettres/
│   ├── rapports/
│   └── entreprises.csv
├── .github/
│   └── workflows/
│       └── ci.yml                  # GitHub Actions
├── requirements.txt
├── README.md
└── ROADMAP.md
```
