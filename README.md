## Solving regression and classification tasks with ML - Abalone
---
> **Note** This repository has been archived.

A Jupyter notebook with an example of solving regression and classification tasks using ML tools and algorithms (**scikit-learn**, **XGBoost**, **LightGBM**).
### Overview:
---
The objective was to learn how machine learning tools and algorithms work in practice. To do this, a dataset was selected as an example, in which the target (the age of abalone) it can be predicted using both regression and classification algorithms.  The Jupyter notebook describes the following stages of work: 
1) exploring and visualizing  the available data with the pandas package and the seaborn and matplotlib libraries;
2) feature transformation and dimensionality reduction using the scikit-learn tools;
3) searching for the best regression and classification models (scikit-learn, XGBoost, LightGBM) and configuring them with search by hyperparameters;
4) evaluating the found best models on test data.
### Setup:
---
The Jupyter notebook was created in a virtual environment configured with Miniconda on a local machine with Windows 10. To run it, also create a virtual environment, check for the packages listed below, and, if necessary, install the corresponding version of them.
### Versions of packages used:
---
python 3.8.5, conda 4.9.2, scikit-learn 0.24.1, xgboost 1.3.3, lightgbm 3.1.1, numpy 1.19.2, pandas 1.1.3, matplotlib 3.3.2, seaborn 0.11.0
### Data: 
---
[Abalone Data Set ](https://archive.ics.uci.edu/ml/datasets/abalone) licensed under a [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/legalcode) license. Source: Dua, D. and Graff, C. (2019). UCI Machine Learning Repository ([web link](http://archive.ics.uci.edu/ml)) Irvine, CA: University of California, School of Information and Computer Science. 
