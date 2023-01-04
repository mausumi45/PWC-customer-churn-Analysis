# PWC-customer-Retention-Analysis
### What is Customer Retention ?
- Customer retention is a metric that measures customer loyalty, or the ability for an organization to keep its customers over time.
- In addition to identifying the number of loyal customers, customer retention can reflect or predict customer satisfaction, repurchase behavior, customer engagement .
### Overview:
I will be working on the telecom churn analysis and here i will be doing a complete EDA process to determine if the customer from that particular telecom industry will leave that telecom service or not meanwhile we will draw some insights from data visualization and analysis so that we could get the factors which will affect the output i.e. churn of the customer.
### Data Collection :
This is the third task of PWC virtual internship  and it was provided by call center retention manager .Below is a short description of each feature inside the data.
- CustomerId - Customer ID
- Gender - Male or Female customerSeniorCitizen - Whether the customer is a senior citizen or not (1, 0)
- Partner - Whether the customer has a partner or not (Yes, No)Dependents - Whether the customer has dependents or not (Yes, No)
- Tenure - Number of months the customer has stayed with the company
-PhoneService - Whether the customer has a phone service or not (Yes, No)
- MultipleLines - Whether the customer has multiple lines or not (Yes, No, No phone service)
- InternetService - Customer’s internet service provider (DSL, Fiber optic, No)
- OnlineSecurity - Whether the customer has online security or not (Yes, No, No internet service)
- OnlineBackup - Whether the customer has online backup or not (Yes, No, No internet service)
- DeviceProtection - Whether the customer has device protection or not (Yes, No, No internet service)
- TechSupport - Whether the customer has tech support or not (Yes, No, No internet service)
- StreamingTv - Whether the customer has streaming TV or not (Yes, No, No internet service)
- StreamingMovies - Whether the customer has streaming movies or not (Yes, No, No internet service)
- Contract - The contract term of the customer (Month-to-month, One year, Two year)
- PaperlessBilling - Whether the customer has paperless billing or not (Yes, No)
- PaymentMethod - The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- MonthlyCharges - The monthly charge amount
- TotalCharges - The total amount charged to the customer
- Churn - Whether the customer churned or not (Yes or No). This is what we want to predict.
- Below is the link of Dataset:
- Link : [Churn-Dataset (1).xlsx](https://github.com/mausumi45/PWC-customer-churn-Analysis/files/10328362/Churn-Dataset.1.xlsx)
### Data Preparation :
I studied the data using Excel for a quick preview . Then ,i imported the data in PowerBI using Get Data option and transformed the data in Power Query Editor.
I replaced the values of churn field from 'No' To 'Stayed' and "Yes" to "Churned".


### EDA using SQL :
 This step invovles 3 steps i.e
 - Analysing all categorical features 
 - Analysing all Numerical feartures
 -  Insights and recommendation
 ### Storytelling Dashboard Using PowerBI :
   This report contains 3 dashboards i.e.
   - Churner Profile
   - Services
   - KPIs
   - Link : https://app.powerbi.com/view?r=eyJrIjoiZjJiYTllZjMtMTY4OC00ZTIzLThlNGQtZWNhNWJlN2U4MDU1IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9
     
    
