# MLP course notebooks

My notebooks from the Machine Learning Practice (MLP) course, cleaned up and reorganised. The original
course colabs were scattered across about 45 files with a fair amount of overlap, so related ones are merged here
and the code updated for current versions of scikit-learn and pandas. Every notebook runs top to bottom.

Most of it is scikit-learn on small classic datasets (California housing, MNIST, iris, abalone, wine
quality, 20 newsgroups, SMS spam). Notebook 00 is a walkthrough of a whole project and a good place to start.

## Contents

| # | Notebook | Topics | |
|---|---|---|---|
| 00 | [End-to-end ML project](notebooks/00_end_to_end_ml_project.ipynb) | the full workflow on California housing: framing, EDA, pipeline, model selection, tuning, test set | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/00_end_to_end_ml_project.ipynb) |
| 01 | [Pandas basics](notebooks/01_pandas_basics.ipynb) | Series/DataFrames, selection, groupby, merge, reshaping | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/01_pandas_basics.ipynb) |
| 02 | [sklearn API and datasets](notebooks/02_sklearn_api_and_datasets.ipynb) | estimators/transformers/predictors, loaders, fetchers, generators | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/02_sklearn_api_and_datasets.ipynb) |
| 03 | [Data preprocessing](notebooks/03_data_preprocessing.ipynb) | imputation (simple, KNN), scaling, encoding, binning, imbalanced data | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/03_data_preprocessing.ipynb) |
| 04 | [Feature selection, PCA, pipelines](notebooks/04_feature_selection_pca_pipelines.ipynb) | filter/wrapper selection, PCA, ColumnTransformer, Pipeline, grid search | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/04_feature_selection_pca_pipelines.ipynb) |
| 05 | [California housing EDA](notebooks/05_california_housing_eda.ipynb) | exploring the dataset used in most regression notebooks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/05_california_housing_eda.ipynb) |
| 06 | [Linear regression and baselines](notebooks/06_linear_regression_and_baselines.ipynb) | cross validation, learning curves, DummyRegressor, permutation test | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/06_linear_regression_and_baselines.ipynb) |
| 07 | [SGDRegressor](notebooks/07_sgd_regressor.ipynb) | learning rates, schedules, early stopping, validation curves | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/07_sgd_regressor.ipynb) |
| 08 | [Polynomial and regularised regression](notebooks/08_polynomial_and_regularised_regression.ipynb) | polynomial features, ridge, lasso, elastic net, hyperparameter search | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/08_polynomial_and_regularised_regression.ipynb) |
| 09 | [Case study: car prices](notebooks/09_case_study_car_prices.ipynb) | EDA, VIF, encoding, linear/lasso/ridge/elastic net | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/09_case_study_car_prices.ipynb) |
| 10 | [Perceptron and classification metrics](notebooks/10_perceptron_and_metrics.ipynb) | MNIST, confusion matrix, precision/recall, PR and ROC curves, one-vs-rest | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/10_perceptron_and_metrics.ipynb) |
| 11 | [Logistic and softmax regression](notebooks/11_logistic_and_softmax_regression.ipynb) | SGDClassifier, LogisticRegression(CV), RidgeClassifier, multinomial | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/11_logistic_and_softmax_regression.ipynb) |
| 12 | [Naive Bayes](notebooks/12_naive_bayes.ipynb) | worked example, TF-IDF, 20 newsgroups, Gaussian NB | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/12_naive_bayes.ipynb) |
| 13 | [k-nearest neighbours](notebooks/13_knn.ipynb) | choosing k, scaling, KNN regression and classification on MNIST | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/13_knn.ipynb) |
| 14 | [Support vector machines](notebooks/14_svm.ipynb) | margins, kernels, C and gamma, SVMs on MNIST | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/14_svm.ipynb) |
| 15 | [Decision trees](notebooks/15_decision_trees.ipynb) | regression and classification trees, pruning, visualising trees | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/15_decision_trees.ipynb) |
| 16 | [Ensembles: regression](notebooks/16_ensembles_regression.ipynb) | bagging, random forest, AdaBoost, gradient boosting, XGBoost, voting, stacking | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/16_ensembles_regression.ipynb) |
| 17 | [Ensembles: classification](notebooks/17_ensembles_classification.ipynb) | MNIST, voting classifiers, class imbalance and resampling | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/17_ensembles_classification.ipynb) |
| 18 | [Neural networks](notebooks/18_neural_networks.ipynb) | MLPRegressor, MLPClassifier on MNIST | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/18_neural_networks.ipynb) |
| 19 | [Text analysis](notebooks/19_text_analysis.ipynb) | bag of words, TF-IDF by hand, SMS spam with logistic regression, combining text and numeric features | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/19_text_analysis.ipynb) |
| 20 | [Large-scale learning](notebooks/20_large_scale_learning.ipynb) | partial_fit, reading CSVs in chunks, HashingVectorizer, streaming text classification | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/20_large_scale_learning.ipynb) |
| 21 | [Image data](notebooks/21_image_data.ipynb) | images as arrays, grayscale/resize/flatten, cats vs dogs, augmentation, error analysis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohanchennupati-sudo/ML-Notebooks/blob/main/notebooks/21_image_data.ipynb) |

## Running

Easiest is the Colab badge, everything needed is already installed there. Locally:

```
pip install -r requirements.txt
jupyter lab
```

Datasets are downloaded on first use (sklearn fetchers, OpenML, UCI). Two need a manual download from Kaggle
(free account), placed in the same folder as the notebook:

* car price case study (09): `CarPrice_Assignment.csv` from
  [car price prediction](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)
* image classification (21): the
  [cats and dogs mini dataset](https://www.kaggle.com/datasets/aleemaparakatta/cats-and-dogs-mini-dataset),
  unzipped into `dataset/` (instructions in the notebook)

Some notebooks (MNIST with SVMs, boosting, neural networks) take a few minutes to run on a laptop.

## Notes

These started as the course's demo colabs. Along the way I fixed a number of bugs in the originals
(data leakage in grid searches, metrics computed on the wrong inputs, parameters that silently did
nothing) and noted them in the notebooks where they matter.
