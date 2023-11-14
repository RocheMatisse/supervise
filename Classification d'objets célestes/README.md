# Classification d'objects célestes

## Données

* obj_ID - Identifiant de l'objet (unique)
* alpha - Right Ascension angle (at J2000 epoch)
* delta - Declination angle (at J2000 epoch)
* u - Ultraviolet filter in the photometric system
* g - Green filter in the photometric system
* r - Red filter in the photometric system
* i - Near Infrared filter in the photometric system
* z - Infrared filter in the photometric system
* label - object class (0 : galaxy, 1 : star, 2 : quasar object)
* redshift - redshift value based on the increase in wavelength

## Modèles développés
* Regressionlogistique
* Kplusprochesvoisins
* SVM (SupportVectorMachine)
* RandomForest
* Gradientboosting
* Agrégatsd’Experts
