# Classification de Fromages par apprentissage profond

# Premier round d'entraînement
Le premier round d'entraînement (entraînement sans tuning des hyperparamètres) a été réalisé dans les fichiers OK_ModelName_FirstRound.ipynb

# Optimisation
L'optimisation des modèles se trouve dans le dossier OptimisationAndTuning avec notamment :
- Le fichier CNN.ipynb pour le tuning de l'architecture du réseau CNN
- Le dossier 1. Batch Size pour le tuning de la taille des minibatchs
- Le dossier 2. SGDOptim pour le tuning d'hyperparamètres avec optimiseur SGD
- Le dossier 3. AdamOptim pour le tuning d'hyperparamètres avec optimiseur Adam
- Le dossier 4. Data Augmentées pour l'apprentissage avec data auglentation
- Le dossier 5. Voting Classifier pour l'implémentation des différents votin classifier

# Data Augmentation :
Le fichier OK_DataAugmentation.ipynb est le fichier que nous avons utilisé pour générer le dataset de données augmentées.
