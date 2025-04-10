# 📊 Comparaison d'Algorithmes d'Optimisation - Reproductibilité

Ce projet permet d’évaluer et de comparer plusieurs algorithmes d’optimisation (Random-5, POEMS, EDA-PSO) en analysant leurs performances à partir de fichiers de résultats `.tdat`.



## 🗂 Description des fichiers

### 🔧 Code
- `Recherche.ipynb` : Script principal contenant les fonctions suivantes :
  - `extract_numbers_from_line()` : Extrait les valeurs numériques d’une ligne.
  - `extract_runs()` : Extrait les séries de résultats d’un fichier.
  - `compute_stats_at_indices()` : Calcule la moyenne et l’écart type à des étapes données.
  - `plot_comparison()` : Génère un graphe comparatif à partir de plusieurs fichiers `.tdat`.

### 📁 Données
Les fichiers `.tdat` contiennent des résultats d'exécution de différents algorithmes sur diverses fonctions (f3, f7, f14, etc.) avec une dimension fixée (DIM3).  
Chaque fichier contient plusieurs "runs" séparés par `%`.

Les fichiers sont stockés dans les dossiers pour chaque algorithme :
R5 pour RANDOM 5
POEMS
EDA-PSO
### 📦 Dépendances
Le projet utilise les bibliothèques Python suivantes :

```txt
numpy
matplotlib
