# Type-II-Diabetes-Prediction
a) Project Objective: 1. To design a Intervention program(which reduces the chance of a person becoming Type II diabetic) using ML models and comparing it with benchmark model in which every person with Glucose>110 was labeled as diabetic. Random Forest model with 100 iterations was the best model which gave a saving of $ 943.15 per person as compared to the benchmark. 2. To design a model which correctly predicts the target class . Again Random Forest model with 100 iterations was the best model with test accuracy of 95.188% with probability threshold of 0.31. 3. To find distinctive characteristic of a Type II diabetic patient. Used the visualisation of a Decision Tree modeled on the top 10 highly predictive attributes for this. b) Data Summary : Data set consisted of 89903 instances with 46 attributes and 1 target class c) Data Preprocessing : 1. Missing value imputation was done using R's MICE package 2. Feature selection was done using R's Boruta package using Wrapper Approach whose criteria was maximizing accuracy d) Classification Algorithms Used: Random Forests, Bagging, Logistic Regression, Decision Trees, Naive Bayes and K Nearest Neighbor e) Tools Used: R for data preprocessing , Weka for training models and Tableau &amp; Matlab for Data Visualization. 
