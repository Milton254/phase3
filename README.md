# Machine_leaning

### PHASE 3 PROJECT
    Student : Milton Kabute
    Date : 10th March 2024

# **Customer Churning Project**
## Predict Customer Churn for Syriatel Telcommunication Company

## **Business Understanding**

### **Background**
SyriaTel, a telecommunications company, provides various services such as mobile, internet, and landline to its customers.
Customer churn, or the rate at which customers cease their relationship with SyriaTel, poses a significant challenge as it directly impacts the company's revenue and profitability.
Identifying and predicting churn patterns is crucial for SyriaTel to proactively address customer attrition, retain valuable customers, and maximize long-term profitability.


### **Objective**
Develop a predictive model that can accurately identify customers at risk of churning from SyriaTel's services.
By predicting churn in advance, SyriaTel can implement targeted retention strategies to mitigate customer attrition, improve customer satisfaction, and enhance overall business performance.

### **Stakeholders**
    -Senior Management
    -Marketing Team
    -Customer Service Reps
    -Investors
    -Communication Regulation Bodies
    -Sales Teams
    -Finance and Accounting Team
    -Product Development Team
    -Social Media Team

### Key Objectives
    What factors contribute to customer churn within SyriaTel's customer base?
    Are there identifiable patterns or trends in customer behavior that precede churn?
    How accurately can we predict which customers are likely to churn in the near future?
    What proactive measures can SyriaTel take to retain at-risk customers and minimize churn rates?
### Data Description
The dataset in Syriatel encompasses the following features
    State: Customer's state of residence
    Account Length: Number of days with the telecom company
    Area Code: Area code of the customer's phone number
    International Plan: Whether the customer has an international calling plan
    Voice Mail Plan: Whether the customer has a voice mail plan .
    Number of Voicemail Messages: Count of voicemail messages received
    Total Day Minutes: Total minutes used during the daytime
    Total Day Calls: Total number of calls made during the daytime
    Total Day Charge: Total charges for daytime usage
    Total Evening Minutes: Total minutes used during the evening
    Total Evening Calls: Total number of calls made during the evening
    Total Evening Charge: Total charges for evening usage
    Total Night Minutes: Total minutes used during the night
    Total Night Calls: Total number of calls made during the night
    Total Night Charge: Total charges for nighttime usage
    Total International Minutes: Total international minutes used
    Total International Calls: Total international calls made
    Total International Charge: Total charges for international usage
    Customer Service Calls: Number of customer service calls made
    Churn: Indicates whether the customer has churned
### Model Success
The model ability to accurately predict customer churn as measured on perfromance metrics such as accuracy, precision, recall, and F1-score. In addition, compare the model to baseline models and provide actionable insights to impliment customer retention stategies.

### Distribution of the data in the dataset

![alt text](image.png)

### Scatterplots Numerical variables vs Churn
![alt text](image-1.png)

### Correlation Heatmap
![alt text](image-2.png)

## Scatterplot
![alt text](image-3.png)

![alt text](image-4.png)

![alt text](image-5.png)

![alt text](image-6.png)

![alt text](image-7.png)

## Distribution of Variables and Churn Status
 
![alt text](newplot.png)

![alt text](<newplot (1).png>)

![alt text](<newplot (2).png>)

![alt text](<newplot (3).png>)

![alt text](<newplot (4).png>)

## Churn Status

![alt text](<newplot (5).png>)

## Gradient Boosting Classifier

![alt text](image-8.png)
## Random Forest Classifier
![alt text](image-10.png)
## SVM 
![alt text](image-11.png)

## Decision Tree
![alt text](image-12.png)

## KNN Classifier
![alt text](image-13.png)

## Logistic Regression
![alt text](image-14.png)

## Classification Model Results
 Classifier  Accuracy  Precision  Recall  F1-Score
0    Gradient Boosting  0.931655   0.761538   0.792  0.776471
1        Random Forest  0.926859   0.780702   0.712  0.744770
3        Decision Tree  0.829736   0.460094   0.784  0.579882
2                  SVM  0.835731   0.459459   0.544  0.498168
5  Logistic Regression  0.690647   0.280528   0.680  0.397196
4                  KNN  0.673861   0.259016   0.632  0.367442

## Confusion Matrix
![alt text](image-15.png)

## Model Evaluation : Gridsearch CV & Random Search Results
Best hyperparameters: {'n_estimators': 150, 'max_depth': 5, 'learning_rate': 0.5}
Accuracy: 0.9268585131894485
Precision: 0.7758620689655172
Recall: 0.72
F1-Score: 0.7468879668049794

## Performance Model Evaluation

Accuracy: 0.9268585131894485
Precision: 0.7758620689655172
Recall: 0.72
F1-score: 0.7468879668049794
ROC-AUC Score: 0.9161523272214388

![alt text](image-16.png)

## Further Model Evaluation

![alt text](image-17.png)

## Separate Test Validation

Accuracy: 0.9460431654676259
Precision: 0.8921568627450981
Recall: 0.728
F1-score: 0.8017621145374448
ROC-AUC Score: 0.9325133991537377

![alt text](image-18.png)