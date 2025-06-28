## Segmentation de Clients d’un Distributeur en Gros avec K-Means

<img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Birmingham_Wholesale_Markets.jpg" alt="Segmentation des clients" height="300" width="900"/>

### 1) Problématique

Dans un contexte de distribution en gros, comprendre les comportements d'achat des clients est essentiel pour développer des stratégies marketing efficaces, optimiser la gestion des stocks et personnaliser les offres. Le jeu de données proposé contient les dépenses annuelles des clients dans plusieurs catégories de produits.

L'objectif de ce projet est d'utiliser l'algorithme de clustering K-Means afin de segmenter les clients en groupes homogènes selon leurs habitudes de consommation. Cette segmentation permettra de :

- Mieux comprendre les profils clients
- Identifier des segments à fort potentiel
- Soutenir les décisions marketing et commerciales

### 2) Jeu de Données

Ce jeu de données provient de l’UCI Machine Learning Repository et recense les clients d’un distributeur en gros. Il contient les dépenses annuelles (en unités monétaires) dans plusieurs catégories de produits.

🔗 Télécharger : https://archive.ics.uci.edu/ml/datasets/Wholesale+customers

### 3) Description des Variables

- Channel : Canal de distribution (1 = Horeca, 2 = Détaillant)
- Region : Région géographique du client (1 = Lisbonne, 2 = Sud, 3 = Autre)
- Fresh : Dépenses annuelles en produits frais
- Milk : Dépenses annuelles en produits laitiers
- Grocery : Dépenses annuelles en produits d'épicerie
- Frozen : Dépenses annuelles en produits surgelés
- Detergents_Paper : Dépenses annuelles en détergents et papier
- Delicassen : Dépenses annuelles en produits de luxe (épicerie fine)

### 4) Méthodologie

1. Prétraitement des données (nettoyage, normalisation)
2. Analyse exploratoire (visualisations, corrélations)
3. Application de K-Means pour segmenter les clients
4. Analyse, visualisation et interprétation des clusters

### 5) Applications Possibles

- Segmentation de marché
- Analyse des habitudes de consommation
- Ciblage marketing
- Personnalisation des offres
- Optimisation de l’approvisionnement

### 6) Librairies Utilisées

- Python : pandas, numpy, scikit-learn, matplotlib, seaborn
- Jupyter Notebook

### 7) Résultats Attendus

- Regroupement pertinent des clients en fonction de leurs dépenses
- Visualisations des clusters 
- Recommandations stratégiques basées sur les segments

### Auteur


Yassine Darif – [LinkedIn](www.linkedin.com/in/darif-yassine)
