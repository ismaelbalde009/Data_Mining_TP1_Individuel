# Data_Mining_TP1_Individuel
Cas 1

Approche : Big Data + Machine Learning (IA)
Orange Guinée traite un très grand volume de données (500 Go de logs sur 5 ans), ce qui relève du Big Data. L’objectif est de détecter des fraudes en temps réel, ce qui nécessite des algorithmes de Machine Learning capables d’apprendre des comportements suspects.

Justification : On manipule de grandes quantités de données et on cherche à détecter des anomalies automatiquement. Cela combine donc stockage/traitement Big Data et intelligence artificielle.

Outil : Apache Spark (avec Spark Streaming)

Cas 2

Approche : Machine Learning (IA supervisée)
La banque veut prédire si un client va rembourser ou non son crédit. C’est un problème de classification supervisée car on dispose probablement de données historiques (clients + résultats).

Justification : Le modèle apprend à partir d’exemples déjà connus pour prédire un résultat futur (remboursement ou défaut).

Outil : Scikit-learn (ex : Logistic Regression ou Random Forest)

Cas 3

Approche : Machine Learning (non supervisé)
L’hôpital regroupe les patients en groupes similaires sans diagnostic préalable. Il s’agit donc d’un apprentissage non supervisé, plus précisément du clustering.

Justification : Il n’y a pas de labels (pas de diagnostic), le système cherche uniquement des similarités entre patients.

Outil : K-means (via Scikit-learn)
