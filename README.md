**Backorder Prediction**
                 
A backorder is an order placed at a given time to fulfill a customer demand which cannot be met at this time due to lack of availability .

The desirability of an organization to balance between holding too much inventory stock vs. holding enough stock to meet the customer needs at any given time is high. However, it is often a struggle between the feasibility and viability of the right approach. And solution to achieve this objective amidst the various
constraints inherent to the organization.

**Requirement**

This study was focused on performing a comparative analysis on different sampling methodologies with penalizing algorithms for an extremely imbalanced dataset. The study also desired to validate which among supervised or unsupervised method is the best fit in an imbalanced dataset case.


**About Data And Features**

The dataset that will be analyzed in this study is taken from Kaggle.

A set of training and test dataset with 1,687,862 and 242,077 observations are available respectively. 

The dataset consists of 15 numerical features and 8 Categorical features along with the target variable.

Among all the features, some are readily available for initial analysis like current inventory details, transit time for product shipment, sales and forecast of products, minimum amount of stocks recommended and any part of product overdue.

**Scripts**

Backorder Prediction EDA : This file contains Exploratory Data Analysis, feature engineering, feature encoding , feature binning performed on the data.

Backorder Prediction Optimizer Classifier : This file contains various machinelearning models trained orginal data, onver-sampled data, under-sampled data and distributed sampled data. The hyperparameters tuning also performed to ehnance the model performance.

Model Interpretation LIME SHAP - This file helps to understand algorithm interpretibility.

AutoEncoder - The unsuperivsed approach to identify backorder

**Models and their results**

Based on all validation and verification on different methodologies, ENN under-sampled method with hyperparameters tuned Random Forest and XGBoost classifiers are the best performers.

In comparing the supervised approach and unsupervised approach, the Autoencoder anomaly detection outperformed and scored the highest in all evaluation matrices

![image](https://user-images.githubusercontent.com/86162045/172370948-6f42b43d-5d6b-475b-b363-607ef35d21a3.png)







