
# Churn Prediction in Telecom Industry Using Logistic Regression

In this project, I have developed a Logistic Regression model to predict Churn in the Telecom Industry. As we all know, Churn is a very crucial element in any customer centric industry, and companies are constantly looking to reduce Churn Rates. This can be done by identifying the most important factors causing Churn, identifying the most vulnerable consumer segment etc. This project uses Python libraries such as Pandas, Numpy, Matplotlib & Seaborn for data preprocessing, creating visuals and deploying feature engineering to deal with categorical values. We have also dealt with class imbalance, a common problem in Churn problems for making our model more efficient. 

## Dataset
https://www.kaggle.com/datasets/blastchar/telco-customer-churn
## Tools/Techniques Used
1. Google Colaboratory
2. Pandas 
3. Numpy
4. Matplotlib
5. Seaborn
6. Feature Engineering
7. Logistic Regression
8. UpSampling
## Steps
1. Reading csv file into google colab.
2. Data Preprocessing
3. Feature Engineering
4. Logistic Regression Implementation
5. Interpreting various classification metrics such as precision, recall, and F1 score.
6. UpSampling to deal with class imbalance.
7. Repeat Steps 4 & 5 
8. Compare the results (pre sampling vs post sampling)
## Conclusion
1. The Accuracy of the model pre-sampling phase was 0.81 with a F1 score of 0.88 for Class 0 (No Churn) & 0.59 for Class 1(Churn) which is minority class. Clearly, F1 score of minority class is low.

2. Post UpSampling accuracy dropped slightly to 0.78 but F1 score for minority class increased to 0.73, which is far better than the previous value.

3. Comparison of F1 scores (pre vs post)-sampling
              Pre     Post   Accuracy
     Class 0  0.88    0.80    0.81
     Class 1  0.59    0.73    0.78

4. Benefits of Sampling - Some of the customers who would churn in reality were predicted as not churned initially due to class imbalance. This could lead to problems and create false impressions for the business.

5. Finally, Monthly Charges and Tenure were known to be the most crucial factors affecting Churn. 
