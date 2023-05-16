# Machine-Learning-model
A machine learning model using Random Forest Regressor and supervised learning to predict dissociation rate constants for the Heatshockprotein 90 only using features based on the ligand

-Experimental dissociations rate constants are published by Liu et al. (2022)

-Create data set with the dissociation rate constants, the names of the ligand and the SMILES codes
-Delete data points with mutation in the protein and ligands with to much structural difference from the other ligands
-80% trainset, 20% testset

-Use RDKit to generate Features based on the SMILES code, optimize them with calculating the feature importance with permutation
-Plot the sorted feature importance

-Optimize the hyperparameters using corss-validation (fold of seven)

-Predict values for the testset

-Calculate different metrics for validation and comparing the ML-model

-Plot expected and predicted values
-Plot errorbars
