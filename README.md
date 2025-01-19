# Algorithme de Recuit Simulé

Ce projet implémente l'algorithme de recuit simulé pour résoudre des problèmes d'optimisation combinatoire, en particulier le **problème du voyageur de commerce (TSP)**. Le recuit simulé est une méthode d'optimisation inspirée de la métallurgie, où un matériau est chauffé puis refroidi lentement pour atteindre un état stable de faible énergie.

---

## Objectifs

- Illustrer l'algorithme de recuit simulé en Python.
- Résoudre un problème réel à partir des données du graphe `gr96`, contenant les coordonnées de 96 villes.
- Comparer les performances avec un chemin optimal fourni dans le fichier `gr96_opt.csv`.

---

## Fonctionnalités

1. **Chargement des données** :
   - Les coordonnées des villes sont extraites de `gr96.csv`.
   - Le chemin optimal de référence est récupéré de `gr96_opt.csv`.

2. **Algorithme de Recuit Simulé** :
   - Génération d'une solution initiale aléatoire.
   - Exploration de solutions voisines en utilisant des propositions de changement simples.
   - Refroidissement progressif pour équilibrer exploration et exploitation.
   - Visualisation et analyse des performances de l'algorithme.

3. **Comparaison avec le chemin optimal** :
   - Calcul du coût du chemin trouvé par le recuit simulé.
   - Évaluation de l'écart avec le chemin optimal.

---

## Structure du Projet

- `recuit_simule.ipynb` : Notebook Jupyter contenant l'implémentation complète.
- `gr96.csv` : Fichier contenant les coordonnées des 96 villes.
- `gr96_opt.csv` : Fichier contenant le chemin optimal pour référence.

---

## Résultats

- L'algorithme de recuit simulé trouve un chemin proche de l'optimal en moins de 1000 itérations.
- Comparaison visuelle et numérique des solutions.

---

## Instructions d'Utilisation

1. Clonez ce projet :
   ```bash
   git clone https://github.com/tawajo/recuit-simule.git
   cd recuit-simule
