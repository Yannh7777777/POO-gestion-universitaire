# Gestion universitaire

Application Python de gestion universitaire pour :
- l'inscription des étudiants ;
- la saisie et le suivi des notes par UE ;
- le suivi des paiements et des soldes ;
- la génération de documents PDF (certificat, bulletin, reçu, liste) ;
- l'export vers Excel.

## Technologie
- Python 3
- Tkinter
- pandas
- numpy
- reportlab
- openpyxl

## Structure du projet

```text
.
├── gestion_universitaire.py
├── requirements.txt
├── README.md
├── .gitignore
├── donnees/
│   └── .gitkeep
├── documents/
│   └── .gitkeep
└── .venv/   # à créer localement
```

## Installation

1. Crée un environnement virtuel :

```bash
python -m venv .venv
source .venv/bin/activate   # Linux/Mac
# ou .venv\Scripts\activate  # Windows
```

2. Installe les dépendances :

```bash
pip install -r requirements.txt
```

3. Lance le logiciel :

```bash
python gestion_universitaire.py
```

## Fichiers générés

- `donnees/ecole.xlsx` : base de données Excel du projet
- `documents/*.pdf` : certificats, bulletins, reçus, listes

## Remarques

- Les fichiers Excel et PDF générés ne sont pas versionnés par défaut.
- Le dépôt contient uniquement le code source, la configuration et la structure du projet.
