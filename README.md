# Construire un modèle de scoring !

Le projet vise à construire un outil de scoring crédit pour la société "Prêt à dépenser", capable d’estimer la probabilité de remboursement d’un emprunteur et de classifier chaque demande en « accordé » ou « refusé ».

Le travail se décompose en deux Jupyter Notebooks :

- `Exploration & feature engineering` : chargement du fichier application_train.csv, nettoyage, analyse des valeurs manquantes et extrêmes, création d’au moins trois nouvelles variables pertinentes (en rapport à celle existante), documentation détaillée.

- `Modélisation & interprétabilité` : construction d’un pipeline scikit-learn, comparaison d’une régression logistique simple et d’un modèle plus complexe, gestion du déséquilibre (resampling ou poids de classes), optimisation des hyperparamètres via GridSearchCV, évaluation avec AUC, accuracy et un score métier intégrant un coût asymétrique des faux négatifs et positifs (FN et FP), analyse de l’importance globale des variables et explications locales avec SHAP.
