# ML_predictions_cac40

Le script suivant permet de récupérer des actions du Cac40 (et autres actifs financiers comme l'Ethereum) ce que nous permettra donc en suite d'entrainer un modèle de ML de prédiction de série temporelle avec la donnée récuperée et de pouvoir prédire quels seront les valeurs du Cac40 pour la suite. 

Nous utilissons de la donnée réel de validation pour vérifier la certitude des prédictions de notre modèle, une fois le modèle validé , nous procédons à utiliser le modèle pour la prédiction d'une valeur inconue, la valuer de l'index Cac40 pour le lendemain suivant. 

Toute la donnée est récupérée depuis yfinance et l'entrainement du model est conçu avec la librairie Tensorflow.
