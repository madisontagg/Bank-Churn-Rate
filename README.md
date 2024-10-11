## Bank-Churn-Rate


#### 📊 Dataset Description:
Account information for 10,000 customers at a European bank, including details on their credit score, balance, products, and whether they have churned.
Data pulled from Maven analytics. (https://mavenanalytics.io/data-playground?accessType=open&order=date_added%2Cdesc&tags=Finance) (Source: Kaggle)(License: Public Domain)

Data Structure: Single table

Number Of Records: 10,000

Number Of Fields: 13

Date Added: 08/16/2024


#### 🪧 Analysis:

Analysis done in DB Browser for SQL Lite.

##### 1A. What attributes are more common among churners than non-churners? 

For churners:
- Average age is 44.8
- Average credit is 645.3
- Average Balance is $91,108.54
- Average Estimated Salary is $101,465.68

For non-churners:
- Average age is 37.4
- Average credit is 651.85
- Average Balance is $72,745.30
- Average Estimated Salary $99,738.39

We can see that most of the churners are higher in age, lower credit score, higher balance and higher salary.

![alt text](https://github.com/madisontagg/Bank-Churn-Rate/blob/main/Averages.png)

Breaking down the data even further, we can see that Churners are majority are Female and French while majority of non-churners are Male and French.

![alt_text](https://github.com/madisontagg/Bank-Churn-Rate/blob/main/MajorityGenderGro2.png)
![alt_text](https://github.com/madisontagg/Bank-Churn-Rate/blob/main/MajorityGenderGeo.png)


##### 1B. Can churn be predicted using the variables in the data?

Churn can be predicted using the findings from the analysis. If we were to predict churners vs. non-churners, we would use the metrics to determine when account holders are nearing the average credit score and account balance.

##### 2. What do the overall demographics of the bank's customers look like?

Grouping the data by female/male and geographical location, we can see that 27% of bank customers are French Males, 23% are French Females, and 14% Spanish Males. 
The average age, credit score and estimated salary are listed below:

![alt text](https://github.com/madisontagg/Bank-Churn-Rate/blob/main/Demographics.png)


##### 3. Is there a difference between German, French, and Spanish customers in terms of account behavior?

In terms of behavior,

###### Germans:
  - Average tenure is 5 years
  - Average Balance is $119,730.12
  - Average Number of Products is 1.5
  - 50% of customers are Active
  - 32% of customers have exited

###### French:
  - Average tenure is 5 years
  - Average Balance is $62,092.64
  - Average Number of Products is 1.5
  - 52% of customers are Active
  - 16% of customers have exited

###### Spanish:
  - Average tenure is 5 years
  - Average Balance is $61,818.15
  - Average Number of Products is 1.5
  - 53% of customers are Active
  - 17% of customers have exited

![alt text](https://github.com/madisontagg/Bank-Churn-Rate/blob/main/Geography.png)

##### 4. What types of segments exist within the bank's customers?

Looking at the Age distribution, the bank customers tend to be around 30-40. Skewed to the left, meaning less and less customers as age increased.

![alt text](https://github.com/madisontagg/Bank-Churn-Rate/blob/main/AgeSegment.png)

Looking at the Credit Score distribution, the bank customers tend to have a credit score between 600-700. 

![alt text](https://github.com/madisontagg/Bank-Churn-Rate/blob/main/CreditScoreSegment.png)


#### 📈 Visualizations:
Line Graphs

#### 👀 Lessons Learned:
SQL is useful for Querying datasets to find underlying patterns and trends. 
