# Projet 7 : Implémentez un modèle de scoring

Ce projet s'appuie sur les données Home Credit disponibles sur la plateforme Kaggle à l'adresse https://www.kaggle.com/c/home-credit-default-risk/data.  
Il consiste à prédire les défauts de paiement d'un organisme de crédit. Puis de rendre les décision du modèle compréhensibles.  
L'exploration et le traitement des données sont inspirés des notebooks Kaggle suivants :
* https://www.kaggle.com/willkoehrsen/start-here-a-gentle-introduction
* https://www.kaggle.com/jsaguiar/lightgbm-with-simple-features


Le modèle est un classifieur LightGBM dont les paramètres sont optimisés par optimisation bayésienne.   
Il est disponilbe sous forme d'API à l'adresse https://home-credit-app-sp.herokuapp.com/.


Le modèle est rendu interprétable via le dashboard dont une version en ligne est accessible à l'adresse https://home-credit-dashboard-sp.herokuapp.com/
