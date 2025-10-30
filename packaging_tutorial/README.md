# Examp - Exemple de packaging Python

Ce dépôt montre étape par étape comment créer, builder, publier et tester un package Python sur **TestPyPI**.

## Structure du projet

packaging_tutorial/
├── LICENSE
├── pyproject.toml
├── README.md
├── src/
│ └── examp/
│ ├── init.py
│ ├── example.py
│ └── example2.py
└── tests/
└── test1.py



- `src/examp/` contient le code du package.
- `tests/` contient des scripts pour tester le package.
- `pyproject.toml` contient la configuration du projet.

## pyproject.toml

```toml
[project]
name = "examp"
version = "0.0.3"
authors = [
  { name="diamankayero", email="diamanka.tck@gmail.com" },
]
description = "A small example package"
readme = "README.md"
requires-python = ">=3.9"
classifiers = [
    "Programming Language :: Python :: 3",
    "Operating System :: OS Independent",
]
license = "MIT"
license-files = ["LICENSE"]

[project.urls]
Homepage = "https://github.com/ton-utilisateur/examp"
Issues = "https://github.com/ton-utilisateur/examp/issues"

## Installation des outils


