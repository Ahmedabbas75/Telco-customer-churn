## 1- Data Description :
- `customerID`: A unique ID that identifies each customer.,
- `gender`: The customer’s gender - Male, Female,
- `SeniorCitizen`: Whether the customer is a senior citizen or not (1, 0),
- `Partner`: Whether the customer has a partner or not (Yes, No),
- `Dependents`: Whether the customer has dependents or not (Yes, No),
- `tenure`: Number of months the customer has stayed with the company,
- `PhoneService`: Whether the customer has a phone service or not (Yes, No),
- `MultipleLines`: Whether the customer has multiple lines or not (Yes, No, No phone service),
- `InternetService`: Customer’s internet service provider (DSL, Fiber optic, No),
- `OnlineSecurity`: Whether the customer has online security or not (Yes, No, No internet service),
- `OnlineBackup`: Whether the customer has online backup or not (Yes, No, No internet service),
- `DeviceProtection`: Whether the customer has device protection or not (Yes, No, No internet service),
- `TechSupport`: Whether the customer has tech support or not (Yes, No, No internet service),
- `StreamingTV`: Whether the customer has streaming TV or not (Yes, No, No internet service),
- `StreamingMovies`: Whether the customer has streaming movies or not (Yes, No, No internet service),
- `Contract`: The contract term of the customer (Month-to-month, One year, Two year),
- `PaperlessBilling`: Whether the customer has paperless billing or not (Yes, No),
- `PaymentMethod`: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)),
- `MonthlyCharges`: The amount charged to the customer monthly,
- `TotalCharges`: The total amount charged to the customer,
- `Churn`: Whether the customer churned or not (Yes or No).

## 2- In Mind Questions
- 2.1 General Questions related to the existence of
  - missing values?
  - wrong datatypes for columns?
  - complete duplicates in the data?
  - outliers in each column?
  - wrong range of values?
  - columns dropped it?

- 2.2 Questions raised during analysis
  - Which is most customer’s `Gender`?
  - What is `age` of most customer’s?
  - Most Customer has a `partner` or not?
  - Most Customer has `dependents` or not?
  - How many `number of months` customers stayed in company?
  - Most customers has a `phone servic`e or not?
  - Most customers has `multiple lines` or not?
  - What is most `internet service` provider used?
  - Most customers saw Internet Service `secure` or not?
  - Most customers prefer `online backup` or not?
  - Most customer have `device protection` or not?
  - Most customer have `tech support` or not?
  - Do most customers `streaming TV` or not?
  - Do most customers `Streaming Movies` or not?
  - What is the most `contract` customers prefer?
  - What is the most `payment` method customers prefer?
  - How many `customers left` within the last month?

 - 2.3 Bivariate Questions between Categorical columns
   - What is Relationship between `each categorical` column and `Churn` column?

- 2.4 Bivariate Questions between Numerical columns
  -  What is Relationship between `each Numerical` column and `Churn` column?
