# Apprentissage supervisé et Data Challenge

## Prédiction de la qualité d'un vin
### Données
Pour ce problème nous disposons de deux Datasets, un dataset d'entraînement et un dataset de test (pour lequel nous ne disposons pas de notes des vins).
Ces deux datasets sont disonibles dans le repo
Ce Dataset contient 13 colonnes:
* wine_ID - identifiant du vin (à conserver dans la soumission mais inutile pour l'entraînement)
* fixed acidity
* volatile acidity
* citric_acidity
* residual sugar
* chlorides
* free sulfur dioxide
* total sulfur dioxide
* density
* pH
* sulphates
* alcohol
* wine_type (rouge: 0, blanc: 1)
* target (disponible uniquement sur le dataset d'entraînement

Les données sont loadées depuis le github repository et le notebook jupyter vient récupérer les données dans le folder data.

### Modèles développés

Le rapport commence par analyser les données et à essayer d'améliorer la qualité du dataset pour améliorer les performances du modèle.
Les modèles développés lors de ce challenge sont:
* Linear regression
* RandomForest
* XGBBoost
* Lgbm

