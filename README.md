# Python-for-Data-Science---NumPy-Pandas-Scikit-Learn
> Résolvons plus de 330 exercices en NumPy, Pandas et Scikit-Learn pour maîtriser la science des données. Affrontons de vrais problèmes, apprenons à exploiter la documentation et Stack Overflow, avec le soutien garanti de l'instructeur Pawel, dans le cadre du suivi d'une formation sur Udemy.

> **Intro**
NumPy (*Numerical Python*) est un paquet fondamental pour le calcul numérique en Python. Il offre une prise en charge des grands tableaux et matrices multidimensionnels, ainsi qu'une vaste collection de fonctions mathématiques de haut niveau pour opérer sur ces tableaux. NumPy est largement utilisé dans le calcul scientifique, l'analyse de données, l'apprentissage automatique (*machine learning*) et bien d'autres domaines.

**Core Features (Fonctionnalités clés) :**

* **Objet Tableau Haute Performance :** Au cœur de NumPy se trouve l'objet `ndarray` (*n-dimensional array*), qui est un tableau multidimensionnel et homogène d'éléments de taille fixe. `ndarray` est plus efficace et plus rapide que la structure de données de liste intégrée de Python.
* **Broadcasting (Diffusion) :** Une fonctionnalité puissante qui vous permet d'effectuer des opérations entre des tableaux de formes et de tailles différentes.
* **Vectorisation :** Permet d'effectuer des opérations complexes sur des tableaux entiers sans utiliser de boucles explicites, ce qui rend le code plus lisible et plus efficace.
* **Fonctions Mathématiques :** Offre un large éventail de fonctions mathématiques, logiques, de manipulation de formes, de tri et bien d'autres.
* **Interopérabilité :** Compatible avec un large éventail d'autres bibliothèques Python, et permet également une intégration facile avec le code C/C++ et Fortran.
* **Extensibilité :** Prend en charge un ensemble étendu de fonctions pour la génération de nombres aléatoires, la transformation de Fourier, l'algèbre linéaire, et plus encore.

**Basic Usage (Utilisation de base) :**

**Installation**
NumPy peut être installé facilement via pip :
`pip install numpy`

**Importation de NumPy**
La bibliothèque est généralement importée avec l'alias `np` :
`import numpy as np`

**Création de tableaux**
Vous pouvez créer des tableaux à partir de données existantes ou en générer selon des critères spécifiques :

```python
# À partir d'une liste
a = np.array([1, 2, 3])

# Zéros, uns, ou valeurs personnalisées
b = np.zeros((3, 3))
c = np.ones((2, 2))
d = np.full((2, 2), 7)

# Intervalle de nombres
e = np.arange(0, 10, 2)

# Nombres également espacés sur un intervalle spécifié
f = np.linspace(0, 1, 5)

```

**Opérations**
Les opérations mathématiques de base sont effectuées élément par élément :

```python
a = np.array([1, 2, 3])
b = np.array([4, 5, 6])

add = a + b  # array([5, 7, 9])
sub = a - b  # array([-3, -3, -3])
mul = a * b  # array([4, 10, 18])

```

**Indexation et Slicing (Découpage)**
NumPy propose des options d'indexation avancées :

```python
a = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])

# Slicing (Découpage)
b = a[:2, 1:3]  # array([[2, 3], [5, 6]])

```

**Fonctions Mathématiques**
NumPy dispose d'une liste étendue de fonctions mathématiques telles que `sum`, `mean`, `min`, `max`, `sqrt`, `sin`, `cos`, etc.

```python
a = np.array([1, 2, 3])

# Somme
s = np.sum(a)  # 6

# Moyenne
m = np.mean(a)  # 2.0

```

**Use Cases (Cas d'utilisation) :**

* Calcul scientifique
* Analyse de données et science des données (*Data Science*)
* Apprentissage automatique (*Machine Learning*) et Intelligence Artificielle
* Traitement du signal image et audio
* Algèbre linéaire, transformations de Fourier, et plus encore

NumPy est un paquet fondamental pour quiconque souhaite effectuer des opérations numériques en Python. Il est souvent utilisé en combinaison avec d'autres bibliothèques telles que Pandas pour la manipulation de données, Matplotlib pour la visualisation (*plotting*), et Scikit-learn pour le *machine learning*.
