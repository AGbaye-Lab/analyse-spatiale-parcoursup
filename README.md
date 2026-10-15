# Analyse spatiale de l'accès à l'enseignement supérieur en Normandie

## 🎯 Objectif du projet
Étude des inégalités territoriales concernant l'offre de formation post-bac (données Parcoursup 2024) en Normandie. L'objectif est de vérifier statistiquement et visuellement la concentration de l'offre.

## 🛠️ Technologies et Méthodes
* **Langage :** R
* **Packages spatiaux :** `sf`, `tmap`, `spdep`
* **Méthodes statistiques :** Indice de Moran, Détection de clusters LISA
* **Données :** Shapefiles IGN (reprojection Lambert 93), Données Parcoursup 2024

## 📊 Résultats clés
* **97,1%** des communes normandes sont sans offre de formation.
* **42,6%** de l'offre est concentrée sur seulement 3 métropoles.
* Confirmation statistique de l'inégalité spatiale avec un indice de Moran de 0.085 (p-value = 0.005).

## 🗺️ Cartographie
*(La carte des clusters LISA sera ajoutée ici prochainement)*

<!-- À faire plus tard : Remplacer le texte au-dessus par : ![Carte des inégalités](nom_de_l_image.png) -->
