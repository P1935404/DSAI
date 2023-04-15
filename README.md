# DSAI
A mini project for SC1015 (Introduction to Data Science and Artificial Intelligence)
<br>
For the ease of reading click here: https://p1935404.github.io/DSAI/
<br>
For wanting to get involved in the machine learning playground, fork the project and have fun~

## Team Members
- Ang Jo Wee
  - Slides
- Park Jihae @pimangnono
  - EDA
  - Data preparation
  - RFE
- Leong Mininn Miko @P1935404
  - Models:
     - Logistic Regression
     - Random Forest
     - Support Vectors Machine
  - Conclusions and evaluations

## Problem Statement
Mushroom hunting, or "shrooming", has become increasingly popular as a recreational activity. However, correctly identifying edible mushrooms from poisonous ones can be challenging, even for experienced mushroom hunters. This poses a risk to the safety of mushroom hunters and their companions, as well as the general public if contaminated mushrooms are consumed.

## Problem Motivation

The goal of this project is to develop an accurate and reliable machine learning model for mushroom classification that classifies edibile and poisonous mushrooms, enhancing the safety of mushroom hunting activities.

## Files
- README.md
- data.csv
- index.ipynb (notebook)
- index.html (html ver where you can view as a website)
- presentation.pptx (presentation deck)

## Models used
We would like to find out using which learning algorithm will be the most accurate. We are comparing 3 models:
- Logistic Regression
- Random Forest
- Support Vector Machines (SVM)

## Conclusion/Insights gained
- We concluded the Random Forest is the best classifier to classify mushrooms among the 3 classifiers. Users are recommended the use random forest to help verify whether the mushorooms are edible or poisonous.
- Also, all 3 have attained a score of around 0.97, which we deem is good enough, we do not need to do ensembling to increase the accuracy of the model.
- We learnt our perception of determining the potential features that can influence the model the most through EDA is different from RFE:
  - RFE: odor_f, gill-size_n, stalk-color-below-ring_w, bruises_f, stalk-root_c
  - EDA: odor_n, odor_f, stalk-surface-above-ring_k, stalk-surface-below-ring_k, ring-type_p
- The features for stalk-root and stalk-color-below-ring are found not to be effective predictors of the class (poisonous, edible). Therefore, we are going to ignore these 2 features when selecting for training data.
- In conclusion, the most important features for training the model include the following: odor_f, gill-size_n, odor_n, stalk-surface-above-ring_k, stalk-surface-below-ring_k, ring-type_p, bruises_f
- <b>Therefore, we concluded the Random Forest is the best classifier to classify mushrooms among the 3 classifiers. Users are recommended the use random forest to help verify whether the mushrooms are edible or poisonous. However, users must noot overrely on the model. It is also important for users to treat the model as a reference and double check the mushrooms before consuming</b>
- <b>Also, all 3 have attained a score of around 0.97, which we deem is good enough, we do not need to do ensembling to increase the accuracy.</b>

## What did we learn from this project?
- Github & Google Colab: collaborating using them
- Data preparation:
  - learning how to one-hot encode data when the dataset we used is categorical
  - learning how to change name of values
- EDA:
  - Learning that EDA is not necessarily graphs, putting them in text is also considered as EDA
- Models Training:
  -   Logistic Regression
  -   Random Forest
  -   SVM
- Evaluation:
  - Using train test accuracy score to check if there's any overfitting occurs
  - Using cross-validation to test the ability of a machine learning model to predict new data

## References
- Data Prep:
  - https://www.kaggle.com/datasets/uciml/mushroom-classification
  - https://datatofish.com/replace-values-pandas-dataframe/
- EDA:
  - https://www.w3schools.com/python/python_functions.asp
  - https://seaborn.pydata.org/generated/seaborn.barplot.html
- Model Training:
  - https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
  - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
  - https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html
- Evaluation:
  - https://medium.com/@dtuk81/confusion-matrix-visualization-fc31e3f30fea
  - https://scikit-learn.org/stable/modules/cross_validation.html
