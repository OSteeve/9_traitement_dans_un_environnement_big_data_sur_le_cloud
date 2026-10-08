# 9_traitement_dans_un_environnement_big_data_sur_le_cloud

""Contexte"" :
La start-up de l'AgriTech, « Fruits » souhaite mettre à disposition du grand public une application mobile qui permettrait aux utilisateurs de prendre en photo un fruit et d'obtenir des informations sur ce fruit.
Le développement de l’application mobile permettra de construire une première version de l'architecture Big Data nécessaire.

""Projet :""
- Développer une première chaîne de traitement des données qui comprendra le preprocessing et une étape de réduction de dimension.
- Tenir compte du fait que le volume de données va augmenter très rapidement après la livraison de ce projet, ce qui implique de:
- Déployer le traitement des données dans un environnement Big Data
- Développer les scripts en pyspark pour effectuer du calcul distribué

Un Alternant a testé une première approche dans un environnement Big Data AWS EMR

""Objectifs :""
Compléter la démarche en ajoutant une étape de réduction de dimension en PySpark. 
Création d’un environnement Big Data, S3 et EMR.

- Data : jeu de données (https://www.kaggle.com/datasets/moltean/fruits)
Images de fruits et légumes
- Notebook de l’alternant :
"Notebook_Linux_EMR_PySpark_V1.0.ipynb"
