
-----

````markdown
# 📦 examp : Un Petit Package d'Exemple

[![PyPI version](https://img.shields.io/pypi/v/examp)](https://pypi.org/project/examp/)
[![Test Status](https://github.com/ton-utilisateur/examp/actions/workflows/main.yml/badge.svg)](https://github.com/ton-utilisateur/examp/actions/workflows/main.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> Un package minimal et didactique créé pour illustrer les étapes de la création, du build et de la publication d'un package Python moderne en utilisant `pyproject.toml`.

---

## ✨ Fonctionnalités

Le package `examp` fournit une fonction simple :

* **`examp.hello()`** : Renvoie une chaîne de salutation.
* **(Ajoutez ici d'autres fonctionnalités si votre package réel en avait !)*

---

## 🚀 Installation

### Prérequis

* Python 3.9 ou supérieur.

### Installation depuis TestPyPI (Exemple)

Puisque ce package est utilisé pour un tutoriel de packaging, nous allons l'installer directement depuis **TestPyPI**.

```bash
# 1. Spécifiez l'index-url de TestPyPI
# 2. Utilisez --upgrade pour vous assurer d'obtenir la dernière version
python -m pip install --index-url [https://test.pypi.org/simple/](https://test.pypi.org/simple/) examp --upgrade
````

### Installation Standard (Pour PyPI)

Si le package était publié sur le PyPI officiel, la commande serait simplement :

```bash
python -m pip install examp
```

-----

## 🛠️ Utilisation

Le package expose la fonction `hello()` dans son module racine (`__init__.py`).

```python
import examp

# Appeler la fonction de salutation
message = examp.hello()

print(message)
# Affiche : "Hello from examp!"
```

-----

## 📂 Structure du Projet

```
packaging_tutorial/
├── LICENSE
├── pyproject.toml
├── README.md <--- VOUS ÊTES ICI
├── src/
│ └── examp/
│     ├── __init__.py
│     └── example.py
└── tests/
    └── test1.py
```

Pour les détails sur la configuration du build (dépendances, versions, etc.), veuillez consulter le fichier **`pyproject.toml`**.

-----

## 🤝 Contribution

Les contributions sont les bienvenues \! Étant donné qu'il s'agit principalement d'un exemple, veuillez consulter les [Issues](https://github.com/ton-utilisateur/examp/issues) pour toute suggestion d'amélioration du tutoriel ou des scripts.

1.  Forker le dépôt.
2.  Créer une branche de fonctionnalité (`git checkout -b feature/nouvelle-fonctionnalite`).
3.  Commiter vos changements (`git commit -m 'Ajout de nouvelle fonctionnalité'`).
4.  Pousser vers la branche (`git push origin feature/nouvelle-fonctionnalite`).
5.  Ouvrir une Pull Request.

-----

## ⚖️ Licence

Ce projet est distribué sous la licence **MIT**. Voir le fichier [LICENSE](https://www.google.com/search?q=LICENSE) pour plus d'informations.

-----

## 👤 Auteur

**Yéro Diamanka** 

  * Lien vers le dépôt : [https://github.com/ton-utilisateur/examp](https://github.com/ton-utilisateur/examp)

<!-- end list -->

```

---

