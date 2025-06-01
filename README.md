# Crime-Data-Mining-Project
Ce projet consiste en une tâche d’exploration et d’analyse de données visant à comprendre les schémas, tendances et facteurs sous-jacents dans les données de criminalité. En explorant et visualisant un jeu de données détaillé sur la criminalité, nous cherchons à découvrir des relations cachées, des zones sensibles et des corrélations entre différentes variables.
## Aperçu du Projet 
Les principaux objectifs de ce projet sont :
- Réaliser une analyse exploratoire complète (EDA) du jeu de données sur la criminalité.
- Visualiser les variables clés liées à la criminalité (par exemple, type d’infraction, heure de la journée, emplacement) afin d’identifier des schémas spatiaux et temporels.
- Analyser les corrélations entre les attributs de la criminalité (par exemple, type d’infraction versus indicateurs démographiques ou socioéconomiques).
- Extraire des informations exploitables pouvant guider les stratégies des forces de l’ordre, l’allocation des ressources et les initiatives de sécurité communautaire.
## Technologies Utilisées
L’analyse est réalisée à l’aide des bibliothèques Python suivantes :
- `pandas`: pour le chargement, le nettoyage et la manipulation des données.
- `numpy`: pour des calculs numériques efficaces et des opérations sur les tableaux.
- `matplotlib`: pour créer des graphiques statiques (par exemple, tendances chronologiques, diagrammes en barres).
- `seaborn`: pour des visualisations statistiques améliorées (par exemple, cartes de chaleur, pairplots).
- `scipy`: pour effectuer des tests statistiques (par exemple, tests du chi², tests t) et en interpréter les résultats.
## Dataset
Le jeu de données comprend des enregistrements détaillés sur les incidents criminels, tels que :
- Détails de l’Incident : identifiant de l’infraction, catégorie de criminalité (par exemple, cambriolage, agression, vol), date, heure et description.
- Informations sur l’Emplacement : coordonnées latitude/longitude, quartier ou commissariat, adresse de la rue.
- Données Victimes/Démographiques : tranche d’âge, genre, origine ethnique (lorsque disponible) et indicateurs socioéconomiques associés aux secteurs de recensement.
- Variables de Résultat : arrestation effectuée (oui/non), statut de clôture (élucidé/non fondé), et données démographiques sur l’arrestation.
- Caractéristiques Contextuelles Supplémentaires : type de propriété (résidentielle, commerciale), présence d’armes ou toute étiquette liée à une activité de gang.
## Visualisations et Analyses  
Le projet comprend:
1. Analyse Temporelle
- Histogrammes du Nombre d’Infractions par Heure/Jour/Mois : identifier les heures de pointe ou les tendances saisonnières.
- Graphiques en Courbes des Taux Mensuels de Criminalité : observer les évolutions d’une année sur l’autre.
2. Analyse Spatiale
- Cartes de Chaleur des Emplacements des Infractions : montrer les zones à forte incidence (points chauds) sur une grille.
- Cartes Choroplèthes par Quartier ou Commissariat : visualiser le taux de criminalité par habitant dans différentes zones.
3. Exploration Catégorielle
- Diagrammes en Barres des Types d’Infractions : comparer la fréquence des différentes catégories de criminalité.
- Diagrammes en Barres Empilées (Type d’Infraction vs. Résultat) : examiner, par exemple, combien d’agressions ont conduit à une arrestation par rapport aux cas non fondés.
4. Corrélations et Tests Statistiques
- Matrice de Corrélation (Carte de Chaleur) : afficher les corrélations entre les variables numériques telles que le nombre d’infractions, le revenu médian, le taux de chômage et la densité de population.
- Tests du Chi² : évaluer l’indépendance entre variables catégorielles (par exemple, type d’infraction et jour de la semaine).
- Tests t ou ANOVA : comparer les moyennes des taux de criminalité entre différents groupes démographiques ou quartiers.
5. Visualisation Multivariée
- Pairplots : observer les relations par paires entre variables continues (par exemple, fréquence des infractions, niveau de pauvreté, temps de réponse de la police).
- Boxplots : comparer les distributions des temps de réponse ou de la gravité des infractions entre différents districts.
