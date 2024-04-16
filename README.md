# Data-Science-test

### Ce travail a pour but de prédire la demande de billet de train en fonction d'un prix proposé, du tems restant avant le départ du dit train et d'autres paramètres tels que la durée de voyage et l'heure d'arrivée du train à la destination souhaitée.

### Il fallait dans un premier temps faire une analyse exploratoire des données en passant par 

  * une verification et suppression des valeurs manquantes (dans un autre cas au lieu de supprimer on pourrait plutot les imputer par une methode appropriées aux données)
  * une verification de la correlation entre les différentes variables
  * une sélection de variable (sélection par Lasso dans notre cas)
  * encodage des données non numériques pour pouvoir les entrainer dans nos modèles

### Ensuite entrainer deux modèles sur nos données afin de pouvoir prédire ladite demande

  * un modèle de gradient boosting avec optimisation d'hyperparamètres (un peu difficile à cause du volume de données) et une MSE = 19.76608619133936
  * un modèle de deep learning avec optimisation de paramètre dans une gridsearch de deux valeurs par paramètres, et une MSE = 14.854723930358887 
