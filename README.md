# Capstone Three Project

# ⏳  Predicting the likelihood of customer churn

This repository contains analysis, visualization, preprocessing and building models that are often used for classification predictive modeling . I am using bank churn data, from Kaggle. My goal is to showcase how to solve classification problems from scratch, using various classification algorithms. This repository consists of 3 files (aside from the ReadME);
  - Presentation Slide PDF file 
  - Main notebook, consists of data analysis, data preprocessing, machine learning modeling and summary of conclusion
  - Final Report, which includes findings, recommendation and further research of the data


# 📂 Dataset
The dataset that was used for this project is 'bank XXX customer Churn', was obtained from ‘Kaggle’ consists of 23 features like age, gender, education level, marital status, income category, total transaction count, total relationship count, total revolving balance,.... I have used 3 different machine learning algorithms to compare the performance of them closely and to see which model performs better predicting customer churn. There were some unnecessary features in our data which I removed.


# 📊 Data Analysis and Data Visualization
In this section I tried visualizing our data, to see how data is distributed in regards to the features.  If there’s a correlation between any features and determine if any of these features are the contributing factor in customer churn .


# 📚 Preprocessing  

 - Check the null values and replace or remove them (data quality assessment)
 - Remove unnecessary features from our data (dimensionality reduction)
 - Convert ordinal values into numerical one (feature encoding)


# 📉 Model Creation
  - Split the data into training and testing sets
  - Perform different machine learning algorithm to find the best model
  
# ☑️ Machine Learning Algorithm that was used:
- RandomForestClassifier
- DecisionTreeClassifier
- XGBClassifier
  
  
# 🔎 Model Evaluation
  - Picking different parameters (hyperparameter tuning) to find the best ones for our model
  - Create the confusion matrix (Precision, Recall) to determine the performance of the our models
  - Using feature importance to see which features are the most influential one in our XGBoost model
   
# 📑 Conclusion
  - We can see from our best accuracy score belongs to XGBoost model with accuracy of 97% followed by RandomForrest and DecisionTree at 96% and 93% accuracy score, respectively. 
  - Since XGboost gives us the best score, we can pick that as our best performing model

# � Recommendations

Based on the observed data and our model prediction, three features play the most important role in churn rate and those are

- Total number of transactions, management should find a way to motivate customers to use their credit card more often, it can be in the form of rewards, cash-back, contests …
- Total Revolving Balance, our data shows the customers who have more revolving balance are more likely to stay with our bank, in comparison with the ones with zero or low revolving balance. It is recommended that management find a way for customers to keep their revolving balance, the solution might be to offer zero interest on the first x amount of revolving balance.
- Total Relationship Count, this refers to the total number of bank’s products each customer is using, it is suggested that management offer ways to encourage our customers in doing more business with our bank, for example opening checking/saving account, credit cards, loans by offering them rewards, cash back, interest free credit cards.

 
# ↗️ Future Improvements
 There are many factors that can contribute to the churn rate, which are missing in this data, it is recommended that the future data include some/all those features as well. Those features are; 

- Credit card annual fee (if any)
- Credit card interest Rate
- Detail customer satisfaction survey, which contains all areas of customer service
- Cash back/ Rewards / sign-ins bonuses (if any)
- Any other data that management is confident will affect the churn rate
 
   
  

