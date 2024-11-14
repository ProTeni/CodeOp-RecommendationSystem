
![Alt Text](./images/pexels-expect-best-79873-351264.jpg)



### Business Problem

**Customer Churn Analysis: A First Data Exploration and Preprocessing Project**

This project is part of my coursework at CodeOp, where I analyze and preprocess customer churn data from a consumer credit card portfolio. The objective is to support a business manager focused on reducing customer attrition by identifying data patterns that may explain why customers are leaving. Though I've worked on other personal projects, this is my first real-world data analysis project within the bootcamp. It marks a significant step in my learning journey at CodeOp and showcases my growing skills in data science.



### **Objective of this Project** :

In this initial exploratory data analysis (EDA) project, my focus is to uncover insights that could help the manager identify key factors driving customer churn. Therefore, the analyses and resulting insights aim to:

- Identify and address data quality issues.
- Conduct an initial analysis to reveal trends, patterns, and potential drivers of customer churn.
- Prepare a clean, well-structured dataset for future modeling work.



### **Data Property & Source** :

- Source: [Kaggle: Bank Churn Data Exploration And Churn Prediction](https://www.kaggle.com/code/thomaskonstantin/bank-churn-data-exploration-and-churn-prediction/input)

- Fields:
Here's an explanation of what each of these fields typically signifies in a customer churn dataset:

   - **CLIENTNUM**: This is the unique identifier for each customer. 

    - **Attrition_Flag**: This field indicates whether a customer has churned or is still active. 

    - **Customer_Age**: This field provides the age of the customer. 

    - **Gender**: The customer's gender (often categorized as male or female).

    - **Dependent_count**: The number of dependents the customer has, which can be an indicator of family size or financial responsibility.

    - **Education_Level**: The customer's highest level of education.

    - **Marital_Status**: The customer’s marital status.

    - **Income_Category**: The customer's income bracket.

    - **Card_Category**: The type or tier of the credit card held by the customer (e.g., blue, silver, gold, platinum).

    - **Months_on_book**: The total number of months the customer has been with the credit card company, which is a measure of customer tenure.

    - **Total_Relationship_Count**: The total number of products or accounts the customer has with the bank, reflecting engagement level.

    - **Months_Inactive_12_mon**: The number of months in the past year in which the customer had no transaction activity.

    - **Contacts_Count_12_mon**: The number of times the customer contacted customer service in the past year.

    - **Credit_Limit**: The maximum amount of credit available to the customer.

    - **Total_Revolving_Bal**: The total balance that rolls over to the next billing period, rather than being paid off, indicating the level of credit dependency.

    - **Avg_Open_To_Buy**: The average amount available for purchases, based on the credit limit minus the revolving balance, which shows available credit.

    - **Total_Amt_Chng_Q4_Q1**: The percentage change in transaction amount between the fourth and first quarter.

    - **Total_Trans_Amt**: The total dollar amount of transactions made by the customer over a certain period.

    - **Total_Trans_Ct**: The total number of transactions the customer made over a certain period.

    - **Total_Ct_Chng_Q4_Q1**: The percentage change in the number of transactions between the fourth and first quarters.

    - **Avg_Utilization_Ratio**: The average utilization of the customer’s credit limit, calculated as the revolving balance divided by the credit limit, which is often a predictor of credit risk.

    - **Naive Bayes Classifier Fields**:

    The last two fields are outputs from a Naive Bayes classifier model. They indicate the likelihood or classification based on certain factors related to attrition


### **Business Questions and Analysis Plan** :


1. **How are customers distributed across different demographics?** (*Customer Demographic Segmentation* )

   - **Objective**: Get a clearer picture of the customer segments 

   

2. **What is the demograph of the inactive users and how constituted the major reaosn fo their attrition?** (*Understanding the inactive users and their demographs*)
    
   - **Objective**: Zoom in on the main segment for the analyses

   2. a. **Could dissatisfaction with customer service be contributing to inactivity?** (*Customer Satisfaction and Service Improvement*)

   - **Objective**:  Assess the reltionship between number of calls placed across t the customer service and the percentage of which are attrited customers.

   

3. **Which inactive customers are high risk and should be excluded and which are wrth targeting?** (*High-Risk Customer Identification and Exclusion*)

  - **Objective**: Identify high-risk customers based on the use of their credit limit. An ideal meanusrement will be: avg_use > credit_limit - (credit_limit * 0.30) or where the avg_utilization_ration < 30 (*Standard practice is to not use more than 30% of the credit limit*)

     

4. **How can we ensure we retain our most engaged customers?** (*Retention of Highly Engaged Customers*)

    - **Objective**: Identify the services our existing customers are engaged with. How can we ensure we keep them constantly engaged based on their demographs- so we do not lose them?
 





##### Based on the question, the libraries used were: Pandas, Numpy, Seaborn, Matplotlib

--------------------------------------

### **Insights from the Analyses**:

- **Question 1**:
graph and then my insight

- **Question 2**:
graph and then my insight

.......

### **General Recommendation and Actions to the business Manager** :
- 
- 








