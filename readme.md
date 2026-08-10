# seattle energy

## Description
Prédiction des émissions de CO2 et de la consommation totale d’énergie de bâtiments non destinés à l’habitation pour la ville de Seattle dans l'état de Washington.  
Le dataset utilisé provient de data.seattle.gov.  
Apprentissage supervisé. Détermination de ces variables continues à l’aide de modèles linéaires (DummyRegressor, Ridge, Lasso) et non linéaires (Bagging, Random Forest, Gradient Boosting).  
RandomForest est retenu comme le meilleur modèle avec un coefficient de détermination (R carré) de 0.7 et la meilleure MAE (Mean Absolute Error). Application d’une validation croisée.  
Évaluation de l’intérêt de l’"ENERGY STAR Score" pour la prédiction d’émissions de gaz à effet de serre.