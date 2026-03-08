# FormationsKS

Support de formation Machine Learning avec des cours (PDF) et des travaux pratiques (notebooks) organisés par session.

## Contenu du dépôt

- `Formation1` a `Formation8` : dossiers de formation.
- Chaque dossier contient :
  - un support de cours au format PDF ;
  - un ou plusieurs notebooks de TP (`.ipynb`) selon la session.
- `Formation6/Titanic` : exemples de modèles et fichiers de soumission.

## Prérequis

- Python 3.10+ recommande
- Jupyter Notebook / JupyterLab

Installation rapide :

```bash
python -m venv venv
source venv/bin/activate
pip install -U jupyter pandas numpy scikit-learn matplotlib seaborn xgboost autogluon
```

## Donnees des TP

Les bases de donnees utilisees dans les TP sont hebergees sur **Kaggle**.

- Recuperer les datasets depuis Kaggle avant d'executer les notebooks.
- Placer les fichiers dans un dossier local `data/` (ignore par Git).

## Utilisation

1. Cloner le repository.
2. Ouvrir le dossier d'une formation.
3. Lire le PDF de cours.
4. Lancer le notebook de TP correspondant.

## Remarques

- Le dossier `data/` est ignore volontairement pour ne pas versionner les jeux de donnees.
- Certains modeles (ex. AutoGluon) peuvent generer des artefacts locaux volumineux.
