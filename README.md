# Recommender system with Python

Projet de système de recommandation de films à partir de la base de données **MovieLens**.
![](https://p.kindpng.com/picc/s/482-4821203_movielens-logo-white-hd-png-download.png)


Nous avons mis en place trois systèmes de recommandation. 

* Les 2 premiers, qui se basent sur le contenu, utilisent soit des titres de films soit des mots clés, pour des résultats réspectivement moyens et plutôt bons. Cependant ces 2 modèles sont plutôt entrée de gamme pourraient être améliorés en utilisant d'autres méthodes d'embedding tel que Word2vec. Word2vec repose sur des réseaux de neurones à deux couches et cherche à apprendre les représentations vectorielles des mots composant un texte, de telle sorte que les mots qui partagent des contextes similaires soient représentés par des vecteurs numériques proches. En bref, Word2vec transforme les verbatimes en matrice et permet de prendre en compte le contexte, contrairement à la mesure TF-IDF qui est plus descriptif
* Le 3ème modèle, reposant sur une approche de filtrage collaboratif (en trouvant des users aux goûts similaires) et la Singular Value Decomposition, obtient également des résultats plutôt bons.


### Librairies python
  - Basics : `numpy`, `pandas`, `json`
  - Machine Learning framework : `scikit-learn`
  - NLP framework : `nlkt`, `re`
  - Plots : `seaborn`, `wordcloud`, `PIL`
