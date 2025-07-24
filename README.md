# 📊 Cas d'Utilisation des Graphiques avec Matplotlib et Seaborn

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.0+-red.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-green.svg)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Un guide complet comparant Matplotlib et Seaborn pour la visualisation de données en Python

## 🎯 À Propos

Ce repository présente une étude comparative approfondie des bibliothèques **Matplotlib** et **Seaborn**, deux outils incontournables pour la visualisation de données en Python. Conçu comme ressource pédagogique et professionnelle, ce projet explore les forces et limites de chaque bibliothèque à travers des cas d'usage concrets.

### 👥 Auteurs
- **Abdoulaye CAMARA**
- **Ibrahima BAH**
- **Superviseur :** Mr Youssouf Vessou TRAORE

## 🔍 Aperçu du Contenu

### Matplotlib vs Seaborn : Le Duel des Géants

| Aspect | Matplotlib | Seaborn |
|--------|------------|---------|
| **Philosophie** | Contrôle granulaire total | Simplicité et esthétique |
| **Courbe d'apprentissage** | Plus raide | Plus douce |
| **Personnalisation** | Maximale | Limitée mais élégante |
| **Cas d'usage** | Publications scientifiques | Analyse exploratoire |

### 📈 Types de Graphiques Couverts

```
📊 Graphiques Étudiés
├── 🔸 Scatter Plot (Graphique de Dispersion)
├── 📈 Line Plot (Graphique en Lignes)  
├── 📊 Histogram (Histogramme)
├── 📦 Box Plot (Boîte à Moustaches)
├── 📊 Bar Plot (Diagramme en Barres)
├── 🔥 Heatmap (Carte de Chaleur)
└── 🎻 Violin Plot (Diagramme en Violon)
```

## 🚀 Démarrage Rapide

### Prérequis

```bash
pip install matplotlib seaborn pandas numpy
```

### Structure du Repository

```
📁 matplotlib-seaborn-guide/
├── 📄 README.md
├── 📖 cas_usage_graphique_matplotlib_seaborn.pdf
├── 📁 examples/
│   ├── 🔸 scatter_plots.py
│   ├── 📈 line_plots.py
│   ├── 📊 histograms.py
│   ├── 📦 box_plots.py
│   ├── 📊 bar_plots.py
│   ├── 🔥 heatmaps.py
│   └── 🎻 violin_plots.py
└── 📁 data/
    └── sample_datasets.csv
```

### Exemple d'Utilisation

```python
import matplotlib.pyplot as plt
import seaborn as sns
import pandas as pd

# Configuration Seaborn pour de beaux graphiques
sns.set_style("whitegrid")
plt.rcParams['figure.figsize'] = (10, 6)

# Exemple rapide : Scatter Plot
data = sns.load_dataset("tips")
plt.figure(figsize=(10, 6))
sns.scatterplot(data=data, x="total_bill", y="tip", hue="day")
plt.title("Relation entre Addition et Pourboire")
plt.show()
```

## 📚 Contenu Détaillé

### 1. 🎯 Objectifs Pédagogiques

- **Analyse critique** des forces et faiblesses de chaque bibliothèque
- **Comparaisons pratiques** sur des cas d'usage réels
- **Recommandations** pour choisir l'outil adapté
- **Exemples concrets** d'application professionnelle

### 2. 🔬 Méthodologie d'Analyse

Chaque type de graphique est analysé selon :

- ✅ **Cas d'utilisation optimaux**
- 🛠️ **Facilité d'implémentation**
- 🎨 **Qualité esthétique**
- ⚙️ **Niveau de personnalisation**
- 📊 **Performance et efficacité**

### 3. 💡 Points Clés

#### Matplotlib : Le Couteau Suisse
- 🔧 Contrôle granulaire total
- 📐 Idéal pour publications scientifiques
- 🏗️ Base de nombreuses autres bibliothèques
- 💪 Flexibilité maximale

#### Seaborn : L'Esthétique Simplifiée
- 🎨 Graphiques beaux par défaut
- 🐼 Intégration native avec Pandas
- 📊 Spécialisé en visualisations statistiques
- ⚡ Développement rapide

## 🗂️ Exemples Pratiques

Le dossier `examples/` contient des implémentations concrètes pour chaque type de graphique :

### 🔸 Scatter Plots
- Analyse de corrélations
- Détection d'outliers
- Visualisation multi-dimensionnelle

### 📈 Line Plots  
- Séries temporelles
- Comparaisons d'évolutions
- Analyse de tendances

### 📊 Histograms
- Distribution de variables
- Analyse de fréquences
- Détection de patterns

### 📦 Box Plots
- Comparaisons de distributions
- Identification d'outliers
- Analyse de dispersion

## 🎯 Cas d'Usage Recommandés

### ✅ Choisir Matplotlib quand :
- Besoin de contrôle précis sur chaque élément
- Création de figures pour publications
- Graphiques complexes ou non-standard
- Intégration dans des applications

### ✅ Choisir Seaborn quand :
- Analyse exploratoire rapide
- Travail avec des DataFrames Pandas
- Besoin de graphiques statistiques
- Priorité à l'esthétique avec peu d'effort

### ✅ Combiner les deux pour :
- Base Seaborn + ajustements Matplotlib
- Workflow d'analyse complet
- Résultats professionnels optimaux

## 📖 Documentation

- 📄 **[Guide Complet PDF](cas_usage_graphique_matplotlib_seaborn.pdf)** - Document détaillé avec analyses théoriques
- 💻 **[Exemples Pratiques](examples/)** - Code source des implémentations
- 🔗 **[Matplotlib Documentation](https://matplotlib.org/stable/)**
- 🔗 **[Seaborn Documentation](https://seaborn.pydata.org/)**

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. 🍴 Fork le projet
2. 🌟 Créer une branche pour votre fonctionnalité
3. 💫 Commit vos changements
4. 📤 Push vers la branche
5. 🔄 Ouvrir une Pull Request

## 📬 Contact

Pour toute question ou suggestion :

- 📧 **Abdoulaye CAMARA** : [ibrahima036]
- 📧 **Ibrahima BAH** : [mrroot]

## 📄 License

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

<div align="center">

**⭐ Si ce projet vous a été utile, n'hésitez pas à lui donner une étoile ! ⭐**

![Matplotlib](https://matplotlib.org/stable/_static/logo2_0.svg)
![Seaborn](https://seaborn.pydata.org/_static/logo-wide-lightbg.svg)

*Créé avec ❤️ pour la communauté Data Science*

</div>
