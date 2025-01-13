## Unemployment Analysis Project
This repository presents the implementation of a data mining course project aimed at analyzing and forecasting unemployment trends across cities and regional councils in Israel. Utilizing a dataset covering ten years (2010-2020), the project applies both supervised and unsupervised machine learning methods to classify unemployment risk, uncover demographic and employment-related patterns, and predict future unemployment rates. The primary objective is to leverage these insights to recommend targeted policy interventions, enhance resource allocation, and aid decision-making for government bodies and local authorities.

### Project Overview
The project involves the following key steps:

1. Data Collection & Preprocessing: Gather and clean the dataset, which includes demographic and employment-related information for cities and regional councils in Israel.
2. Feature Engineering: Create relevant features for predicting unemployment trends.
3. Modeling: Build machine learning models for binary classification, including Logistic Regression, Random Forest, XGBoost, SVM, and k-NN.
4. Evaluation: Assess model performance using evaluation metrics such as accuracy, precision, recall, and F1-score.
5. Unsupervised Learning: Conduct clustering and anomaly detection to identify trends and insights.
6. Visualization: Present findings using graphs and charts for a clearer understanding of the results.

### Dataset
The dataset used in this project is from Data.gov.il. it contains 28,668 rows and 13 features with demographic and employment-related data for cities and regional councils in Israel. The key features include:

1. Urban Demographics: city name, district, council type.
2. Employment Data: Total job seekers, unemployment rates, placement success, gender distribution, and academic background.

Each city appears 24 times in the dataset, corresponding to monthly data across ten years.

### Libraries Used
#### Data Analysis and Manipulation:
* pandas
* numpy
2. numpy
#### Visualization:
seaborn
matplotlib.pyplot
matplotlib.cm (for colormaps)
#### Machine Learning:
scikit-learn
xgboost
#### Clustering:
scikit-learn
scipy.cluster.hierarchy (for hierarchical clustering)

### Results
1. Achieved the highest average ROC-AUC score (0.9961) with the best-performing supervised model.
2. Identified key factors influencing unemployment, such as education level and region.
3. Clustering analysis revealed distinct groups of cities with similar unemployment trends.

### License
This project is licensed under the MIT License.

### Authors
This repository is managed by Yarden Samuel and Renana Fried. For any questions or feedback, please contact us via GitHub.


