# Projet Python - Quels sont les facteurs qui influencent l'orientation et la réussite au baccalauréat ?

Ce projet, réalisé par Louison Guegaden et Ryan Borhani vise à étudier et analyser les facteurs de différenciation des étudiants dans leur orientation et leurs résultats au baccalauréat.
L'analyse se divise en 3 parties : une analyse par genre, une analyse géographique, et une analyse basée sur l'IPS (indide de position sociale) des lycées.

## Données
Les bases de données proviennent du site data.gouv et de l'INSEE. Certaines données ont été obtenues par l'API data.gouv. Pour des raisons de lenteur d'exécution de code, la partie faisant appel à l'API a été séparée du reste, et peut être obtenue à partir du notebook "Importation BDDs API.ipynb".
Toutes les données se trouvent dans le dossier BDD.

## Etude
L'étude se trouve dans le notebook "Etude de l'orientation et de la réussite au baccalauréat.ipynb". Le dossier git peut être téléchargé et le notebook lancé pour afficher l'ensemble des graphs.

## Revue de la littérature 

Les recherches antérieures soulignent les obstacles systémiques auxquels sont confrontés les jeunes issus de zones géographiques éloignées ou de milieux modestes. De plus, la faible diversité de genre dans certaines filières interroge la structure éducative française.

- Plus de la moitié (55 %) des jeunes femmes sont diplômées de l'enseignement supérieur contre à peine 45 % des jeunes hommes. Parmi les admis au baccalauréat de la session 2022, 52 % sont des filles. (Source : MESR-DGESIP/DGRI-SIES, enquête 2021 sur l'insertion professionnelle des diplômés de l'université).
- Au lycée, les filles sont nettement moins nombreuses dans la voie professionnelle (38 %) et plus nombreuses dans la filière générale (56 %). Dans les filières professionnelles et technologiques, les filles sont largement majoritaires dans les spécialités et les séries qui débouchent sur des métiers très féminisés. En 2020, les filles obtiennent plus souvent le baccalauréat (+ 3 points). (Source : INSEE, “Femmes et Hommes, L’égalité en question.”, édition 2022).
- Au baccalauréat professionnel, les candidats des académies de Nantes et de Rennes réussissent le plus souvent. Plus de 95 % des candidats au baccalauréat général sont admis en Corse mais moins de 70 % à Mayotte. (Source : Ministère de l'Éducation Nationale, "Géographie de l’École.", 2017)
- Dans le privé sous contrat, les établissements à faibles IPS (inférieur à 90) affichent proportionnellement de meilleurs résultats. Parmi les lycées professionnels ayant un taux de réussite au bac supérieur à 95%, 10% ont un IPS inférieur à 90. Dans le public, ils ne représentent que 4,8% des établissements qui performent le mieux. (Source : Ministère de l'Éducation nationale, 2023).
- "L’origine sociale des élèves est le plus souvent appréhendée par la profession et catégorie sociale (pCS) de leurs parents. l’idée de construire un indice dérivé de la pCS, qui puisse mesurer la position sociale des élèves répond à deux besoins issus des études statistiques des performances scolaires des élèves. En premier lieu, la pCS des parents est certainement la variable la plus utilisée dans le champ des études sur les inégalités sociales à l’école, mais elle peut montrer certaines limites à remplir son rôle de repérage central des disparités de réussite scolaire. Cet indice aurait pour vocation de synthétiser davantage de dimensions (sociales, économiques, culturelles). En second lieu, le profil social d’ensembles plus larges que le simple individu se laisse difficilement appréhender à l’aide de la nomenclature des groupes socioprofessionnels. une mesure quantitative permet de passer plus facilement du niveau de l’élève à celui de la classe ou de l’établissement scolaire. un indice peut ainsi servir d’instrument pour la mesure des effets de contexte qui sont au cœur des problématiques actuelles de la sociologie de l’éducation. En outre, il peut donner une mesure plus fiable et plus robuste de la mixité sociale dans les établissements."  (Source : Ministère de l’Éducation Nationale, “Construction d’un indice de position sociale des élèves”, 2016). 
