# Analyse et Modélisation de la Volatilité du Bitcoin avec des Modèles GARCH

Ce projet analyse la volatilité du Bitcoin (BTC-USD) de janvier 2018 à aujourd'hui en utilisant des modèles économétriques avancés. L'objectif est de comparer la performance de différents modèles pour capturer les dynamiques de risque spécifiques aux crypto-actifs.

---

### Objectifs Clés
- Comparer un benchmark simple (volatilité historique) à des modèles GARCH.
- Tester la présence d'un "effet de levier" (asymétrie) dans la volatilité du Bitcoin.
- Déterminer le modèle le plus performant pour décrire le risque du BTC.

### Conclusions Principales
- Le modèle **GJR-GARCH(1,1)** offre le meilleur ajustement statistique (scores AIC/BIC plus bas).
- Contrairement aux marchés actions, aucune preuve statistique d'un **effet de levier** significatif n'a été trouvée.
- La volatilité du Bitcoin est caractérisée par une **très forte persistance** : les chocs de marché ont un effet durable.

---

### Technologies Utilisées
- **Langage :** Python 3.x
- **Librairies Principales :** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Arch.

---

### Comment Lancer le Projet
1. Clonez ce dépôt.
2. Installez les dépendances nécessaires : `pip install -r requirements.txt`
3. Lancez Jupyter Lab ou Jupyter Notebook et ouvrez le fichier situé dans le dossier `/notebooks`.