# 📊 Statistiques Appliquées et Analyse de Données de Santé

## 👩‍💻 Réalisé par

**Mina El Aacharate**
Data Analyst Junior

---

## 🎯 Objectif du projet

Ce projet vise à analyser des données de santé publique afin de comprendre la relation entre :

* 💰 Les dépenses de santé (`Spending_USD`)
* ❤️ L'espérance de vie (`Life_Expectancy`)

L'objectif est de produire des analyses fiables et interprétables pour aider à la prise de décision.

---

## 🧠 Phase 1 – Concepts statistiques

Cette phase consiste à maîtriser et documenter les notions suivantes :

### 📌 Statistiques descriptives

* Moyenne
* Médiane
* Variance
* Écart-type
* Histogramme
* Boxplot

### 📌 Concepts fondamentaux

* Population vs Échantillon
* Probabilités et distributions :

  * Bernoulli
  * Binomiale
  * Poisson
  * Normale
  * Student
  * Chi-deux

### 📌 Théorème Central Limite

* Principe
* Importance en analyse de données

### 📌 Tests statistiques

* Hypothèses H0 / H1
* p-value
* Interprétation des résultats

---

## ⚙️ Phase 2 – Analyse des données

### 📂 Dataset utilisé

* `healthexp.csv`

---

## 🔍 Étapes d’analyse

### 1. Classification des variables

* `Country` → Variable discrète
* `Spending_USD`, `Life_Expectancy` → Variables continues

---

### 2. Analyse descriptive

#### 📊 Spending_USD

* Analyse statistique (mean, min, max...)
* Histogramme et Boxplot
* Interprétation de la moyenne

#### ❤️ Life_Expectancy

* Analyse statistique
* Visualisations
* Interprétation globale

---

### 3. Analyse temporelle

* Évolution de l'espérance de vie dans le temps
* Amélioration des visualisations (lisibilité, filtres)

---

### 4. Comparaison entre pays

* 🇩🇪 Allemagne vs 🇬🇧 Royaume-Uni
* Analyse des dépenses de santé
* Comparaison des moyennes

---

### 5. Analyse par pays

* Histogrammes et boxplots par pays
* Détection des valeurs aberrantes

---

### 6. Cas des États-Unis 🇺🇸

* Relation entre dépenses et espérance de vie
* Visualisation (scatter plot)
* Identification d'une valeur aberrante :

  * Dépenses élevées mais espérance de vie relativement faible

---

## 📈 Analyses statistiques avancées

### ✔️ Corrélation (Pearson)

* Mesure de la relation entre dépenses et espérance de vie
* Interprétation de la force de la corrélation

### ✔️ p-value

* Test de significativité
* Validation statistique des résultats

---

### ⚖️ Test d’hypothèse

#### Allemagne vs Royaume-Uni

* Test t de Student
* Vérification si les moyennes sont significativement différentes

#### 🇺🇸 Bonus – Croissance de l'espérance de vie

* Test de l'affirmation : +0.3 an/an
* Niveau de confiance : 98%

---

## 🧪 Outils utilisés

* Python 🐍
* Pandas
* Matplotlib
* Seaborn
* Scipy

---

## 📊 Résultats clés

* ✔️ Corrélation entre dépenses de santé et espérance de vie
* ✔️ Présence de valeurs aberrantes (ex : États-Unis)
* ✔️ Différences entre pays analysées statistiquement
* ✔️ Importance des tests statistiques pour valider les conclusions

---

## ⚠️ Limites de l’analyse

* Corrélation ≠ causalité
* Données limitées à certains pays
* Facteurs externes non pris en compte (mode de vie, politique...)

---

## 🚀 Conclusion

Ce projet montre que :

* Les dépenses de santé influencent l’espérance de vie
* Mais ne suffisent pas à expliquer totalement les résultats
* L’analyse statistique est essentielle pour une prise de décision fiable

---

## 📌 Améliorations possibles

* Ajouter plus de pays
* Intégrer d'autres variables (éducation, alimentation…)
* Utiliser des modèles de machine learning

---

## 📎 Livrables

* 📄 Documentation Phase 1
* 📊 Notebook Phase 2
* 🎤 Présentation orale

---

## 🙌 Remarque

Ce projet permet de relier la théorie statistique à une application concrète en data analysis dans le domaine de la santé publique.

---
