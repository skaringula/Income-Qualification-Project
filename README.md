# Income-Qualification-Project

This project was completed to fulfil the mandatory criteria towards Machine Learning module of my Data Science Master's Program at Simplilearn. 

### Objective: 
To identify the level of income qualification needed for the families for social welfare program in Latin America.

Many social programs have a hard time ensuring that the right people are given enough aid. It’s tricky when a program focuses on the poorest segment of the population. This segment of the population can’t provide the necessary income and expense records to prove that they qualify.

In Latin America, a popular method called Proxy Means Test (PMT) uses an algorithm to verify income qualification. With PMT, agencies use a model that considers a family’s observable household attributes like the material of their walls and ceiling or the assets found in their homes to classify them and predict their level of need. While this is an improvement, accuracy remains a problem as the region’s population grows and poverty declines.

The Inter-American Development Bank (IDB) believes that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance.

Project Description: 
- Understand input dataset since dataset is huge and contains 143 columns and 9557 observations altogether in training data provided.
- Complete pre-processing of data including missing value treatment in various columns. 
- Check and drop one of the highly correlated feature pairs in household and individual features in dataset. 
- Convert object type variables into numerical data.
- Create a Machine Learning model with Random Forest Classifier.
- Evaluate performance of model using various metrics such as confusion matrix and classification report. 
- Improve model performance using GridSearchCV.
- Find important features among the predictor variables and comment on their importance in model performance.
