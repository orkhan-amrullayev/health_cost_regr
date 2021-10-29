## 2. Insurance Cost Prediction

A health insurance firms can make money if it collects more than it spends on the medical care of its beneficiaries. Even though some conditions are more prevalent for certain segments of the population, medical costs are difficult to predict since most money comes from rare conditions of the patients. The objective of this paper is to accurately predict insurance costs based on people’s data listed below.

age: age of primary beneficiary
sex: insurance contractor gender, female, male
bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
children: Number of children covered by health insurance / Number of dependents
smoker: Smoking
region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
charges: Individual medical costs billed by health insurance (dependent)

Content
1. Importing libraries and reading dataset
2. General exploratory Data Analysis
3. Relationship between features
4. Data Preparation
5. Conclusion of EDA
6. Label encoding
7. Modelling
8. DecisionTree
  - RandomForest
  - KNeighbors
  - AdaBoostRegressor
  - GradientBoosting
  - XGBRegressor
9. Cross Validation
10. Model Accuracy Comparison
