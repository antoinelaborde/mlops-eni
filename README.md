# ENI - MLOps

## Installation
Prérequis:
- git
- dvc
- python3
- pip
- virtualenv

Instructions:
1. Créer un environnement
```shell
python -m venv .venv
source .venv/bin/activate  # mac/linux
.venv\Scripts\activate  # windows
```

2. Installer
```shell
pip install -r requirements.txt
```

## Initialiser le projet
```shell
git init
dvc init
dvc add data/ 
```

```shell
git add data.dvc .gitignore .dvc/
git commit -m "track data with DVC"
```


