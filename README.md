# Gestion universitaire

Ce projet a été préparé pour l'hébergement web.

## Stack
- Python
- Flask
- Gunicorn

## Lancement local

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

## Hébergement

Le projet est prêt pour un déploiement sur Render via le fichier `render.yaml`.

1. Connecte le dépôt GitHub sur Render.
2. Sélectionne le service web.
3. Render détecte automatiquement `render.yaml`.
4. La URL publique est générée par Render après le premier déploiement.

Remarque : la vraie logique métier du système universitaire n'est pas encore présente dans ce dépôt. Ce scaffold sert de base de déploiement web prête à recevoir l'application complète.
