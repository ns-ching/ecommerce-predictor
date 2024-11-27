# ecommerce-predictor
ML model that predicts delivery times for packages ordered online

This model integrates five datasets from Kaggle (https://www.kaggle.com/datasets/bytadit/ecommerce-order-dataset?resource=download) that detail package information and arrival times.

Several model architectures were run with various hyperparameters tuned and different PCA N components. The best model was XGBoost with no PCA and a max depth of 18, which yielded an error of 1.3 days.
