# Kaggle Tabular Playground Series ML (Aug22)

This is my Python code (Jupyter Notebook) for the Kaggle competition "Tabular Playground Series" (August 2022 edition: https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview).

The aim of the competition is to use machine learning to create a model that predicts succes/failure for new products prototypes created by an industrial company.

This notebook contains recipies for data elaboration (tackling missing values, categorical variables, etc.) and exploration over different ML models (such as Gradient Boosted Decision Trees, Support Vector Machines) to find the most appropriate one for this problem.

Gradient Boosted Decision Trees provide the best results in terms of ROC AUC, whereas Kernelized Support Vector Machines are found to perform much worse, even after parameters tuning.

Train and test datasets are train.csv.zip and test.csv.zip files respectively. The predicted outcome with the chosen best model is saved into submission.csv. The Jupyter Notebook containing the code is TabularPlaygroundSeries_Aug2022.ipynb.
