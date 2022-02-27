# Data-driven-healthcare
Git repository for group project

The dataset chosen for the project is from here:
https://archive-beta.ics.uci.edu/ml/datasets/cervical+cancer+risk+factors

Dataset description:
Tabular data on risk factors for cervical cancer (858 patients)

Questions we want to answer:
Can we use these data to predict (classify) cancer?
Can a glassbox model be used to highlight the global features that drive the prediction?

Files: 

- risk_factors_cervical_cancer.csv : raw data
- CervialCancerRisks_visualizeEBM.ipynb : script to inspect data, split it into test and training set and visually explore the global and local explanations of model outcomes
- CervialCancerRisks_crossValidation.ipynb : running explainable boosting machine in a cross-validated manner (explainability features not included)
- CervialCancerRisks_crossValidation_with_blackbox.ipynb : running the same cross validation as above, but for the two blackbox models (random forest and gradient boosting) 
