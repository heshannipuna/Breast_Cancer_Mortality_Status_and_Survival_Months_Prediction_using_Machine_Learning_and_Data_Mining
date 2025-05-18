
# Breast Cancer Mortality Status and Survival Months Prediction using Machine Learning and Data Mining

This project aims to develop predictive machine learning models for assisting healthcare professionals in identifying breast cancer patients at higher risk of mortality and estimating survival periods. The dataset is derived from historical SEER cancer registry data, and the goal is to build a reliable decision-support tool using classification and regression models.


## Objectives

- **Classification:** Predict whether a breast cancer patient will survive or not using Logistic Regression, K-Nearest Neighbours, and Naïve Bayes classifiers.

- **Regression:** Estimate survival months for patients predicted not to survive using Decision Tree regressors.

- **Hyperparameter Optimization:** Fine-tune models using GridSearchCV for improved accuracy and recall.

- **Model Evaluation:** Assess models using metrics such as confusion matrix, classification report, ROC-AUC, MAE, MSE, and R².

## Project Structure

```notebooks/ ``` — Jupyter Notebooks for data understanding, classification modelling, and regression modelling.

``` Final_Python_Notebook_1.ipynb  ```

``` Final_Python_Notebook_2.ipynb  ```

``` Final_Python_Notebook_3.ipynb ```


```dataset/ ``` — Input dataset used for model training and testing.
## Techniques Used

- Data Preprocessing: Scaling, encoding, feature selection

- Supervised Learning Algorithms: Logistic Regression, KNN, Naïve Bayes

- Regression Trees: Fully-grown and pruned Decision Trees

- Evaluation: Accuracy, Recall (Dead class focus), ROC-AUC, MAE, MSE
## Dataset Source

Breast cancer records from the [_**SEER Breast Cancer Data**_](https://ieee-dataport.org/open-access/seer-breast-cancer-data)
## Use Case

The models support oncologists and researchers in:

- Early screening of high-risk patients.

- Tailoring treatment plans based on predicted mortality risk.

- Prioritizing care for patients with shorter expected survival.
## License
This project is for academic purposes only.

© 2025, University of Westminster | Module: 5DATA002W.2

