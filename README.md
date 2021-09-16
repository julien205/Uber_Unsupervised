# Uber_Unsupervised

Dans ce projet nous utilisons des modèles de Machine Learning non-supervisés afin de clusteriser des données non labelisées pour définir où seront situées les zones de fortes demandes de taxi dans la ville  de New-York.

Nous avons opté pour une méthode d'exploration de l'efficacité des modèles sur les différents jeux de données proposés.
  -sur les données géographiques, nous avons testé KMeans et Dbscan, et ce en fonction de différents facteurs temporels tels que l'heure de la journée, le jour de la semaine ou le mois. Les résultats sont présentés sous le forme de cartes.
  -Sur des données temporelles( horaires de la journée à la minute transformés afin de conserver le caractère cyclique pendant l'entrainement du modèle, ici Kmeans) liée à un élément catégoriel qui désigne une zone de New York. Grace à une API de géolocalisation, nous avons réussi à définir les coordonnées géographiques de ces zones afin de pouvoir présenter le résulat sur une carte de la ville.
