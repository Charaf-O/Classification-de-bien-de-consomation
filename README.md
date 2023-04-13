## Projet de classification d'articles

### Introduction

Dans ce projet, nous avons pour objectif d'automatiser l'attribution de catégorie pour des articles postés sur une place de marché. Actuellement, les vendeurs sont chargés de catégoriser leurs articles, ce qui entraîne une faible fiabilité de l'attribution des catégories. Pour remédier à cette situation, nous allons réaliser une étude de faisabilité d'un moteur de classification d'articles basé sur une image et une description.

### Données

Le jeu de données contient des articles avec leur description et une photo associée.


### Approche utilisé:
    Approches de type "bag-of-words" :
        - Comptage simple de mots
        - TF-IDF
    
    Approche de type word/sentence embedding:
        - Word2Vec
        - BERT
        - USE (Universal Sentence Encoder)

    Algorithme de type:
        - SIFT / ORB / SURF
        - CNN Transfer Learning

### Méthodologie
Pour réaliser l'étude de faisabilité, nous avons suivi les étapes suivantes:

    - Prétraitement des descriptions des produits et des images
    - Réduction de dimension
    - Clustering
    - Visualisation des résultats sous forme de graphiques en deux dimensions
    - Calcul de similarité entre les catégories réelles et les clusters
