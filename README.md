### Customer Churn Prediction

Customer churn, also known as customer attrition, occurs when clients discontinue their relationship with a business. This phenomenon can significantly affect a company's revenue, making it essential for organizations to understand why customers leave and to implement strategies to minimize churn. One effective approach is to identify groups of customers who are more likely to leave and then apply targeted retention efforts. Additionally, by leveraging data analytics and machine learning, companies can forecast which customers might churn in the future and proactively engage them to improve retention.

In this project, we will develop a basic predictive model for customer churn using the Telco Customer Churn dataset. We will apply various classification algorithms to distinguish customers who have left from those who have stayed. Python libraries such as pandas will be used for data handling, and matplotlib will assist in visualizing the data.

#### Steps to Build the Customer Churn Prediction Model

1. Import necessary libraries  
2. Load the dataset  
3. Perform exploratory data analysis (EDA)  
4. Detect outliers using the Interquartile Range (IQR) method  
5. Clean and preprocess the data  
6. Apply one-hot encoding to categorical variables  
7. Rearrange columns for better organization  
8. Scale features to normalize data  
9. Select the most relevant features  
10. Build and evaluate models using:  
    - Logistic Regression  
    - Support Vector Classifier (SVC)  
    - Decision Tree Classifier  
    - K-Nearest Neighbors (KNN) Classifier  
