Q.4 Limites :
	
Il y a tout d'abord un chevauchement des genres, certains films qui ont plusieurs genre donc un film très bien noté dans plusieurs genres peut dominer les premières places dans différentes catégories.
La gestions des valeurs nulles et manquantes dans les colonnes genres et averageRating peut affecter l'analyse. De plus les notes et la popularité des films peut varier au cours du temps, il faudra mettre à jour les classements.



Q.4 On pourrait utiliser un outil de planification automatique comme apache airflow ou un outil de cloud pour automatiser le téléchargement de données IMDB. Par la suite pour stocker les données on pourrait utiliser des outils cloud comme Amazon Web Services (Aws).

    Pour traiter les données on peut développer une pipeline Extract Transform Load (ETL) pour filtrer les films et charger les bases de données.
    Ainsi pour la partie analyse de données on peut utiliser des outils comme big query pour stocker et mettre quotidiennement à jour la base de données.
    Pour exposer les données on peut développer des api qui permettront au site web d'afficher les requête à jour ou un tableau de bord intéractifs commme Tableau ou Power BI.
 
Q.5 On peut d'abbord stocker les données exportés dans dans un datawarehouse (Google BigQuery par exemple), utiliser une pipeline ETL pour transformer nettoyer et normaliser les données. Pour éviter un impact sur les performences du site web ces traitements doivent être réalisés hors ligne par exemple.
    