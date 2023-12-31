## 1- Data Description :
- `customerID`: A unique ID that identifies each customer.
- `gender`: The customer’s gender - Male, Female.
- `SeniorCitizen`: Whether the customer is a senior citizen or not (1, 0).
- `Partner`: Whether the customer has a partner or not (Yes, No).
- `Dependents`: Whether the customer has dependents or not (Yes, No).
- `tenure`: Number of months the customer has stayed with the company.
- `PhoneService`: Whether the customer has a phone service or not (Yes, No).
- `MultipleLines`: Whether the customer has multiple lines or not (Yes, No, No phone service).
- `InternetService`: Customer’s internet service provider (DSL, Fiber optic, No).
- `OnlineSecurity`: Whether the customer has online security or not (Yes, No, No internet service).
- `OnlineBackup`: Whether the customer has online backup or not (Yes, No, No internet service).
- `DeviceProtection`: Whether the customer has device protection or not (Yes, No, No internet service).
- `TechSupport`: Whether the customer has tech support or not (Yes, No, No internet service).
- `StreamingTV`: Whether the customer has streaming TV or not (Yes, No, No internet service).
- `StreamingMovies`: Whether the customer has streaming movies or not (Yes, No, No internet service).
- `Contract`: The contract term of the customer (Month-to-month, One year, Two year).
- `PaperlessBilling`: Whether the customer has paperless billing or not (Yes, No).
- `PaymentMethod`: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).
- `MonthlyCharges`: The amount charged to the customer monthly.
- `TotalCharges`: The total amount charged to the customer.
- `Churn`: Whether the customer churned or not (Yes or No).
_______________________________________________________________________________________
## 2- In Mind Questions
- ### 2.1 General Questions related to the existence of
  - missing values?
  - wrong datatypes for columns?
  - complete duplicates in the data?
  - outliers in each column?
  - wrong range of values?
  - columns dropped it?

- ### 2.2 Questions raised during analysis
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

 - ### 2.3 Bivariate Questions between Categorical columns
   - What is Relationship between `each categorical` column and `Churn` column?

- ### 2.4 Bivariate Questions between Categorical and Numerical columns
  -  What is Relationship between `each Numerical` column and `Churn` column?
_______________________________________________________________________________________
## 3- Conclusion

- ### 3.1 Reached Results during analysis
  - `Male` is the most customer’s gender.
  - Most customers don't `senior citizen`.
  - Most customers don't have a `partner`.
  - Most customer’s don't have `dependents`(30.0% of customer’s under 18 years).
  - Most customer’s has a `phone service`.
  - 42.2% has `MultipleLines`.
  - 78.4% has `Internet Service`(Most customer’s has fiber optic service).
  - Most customers saw Internet Service has `no security`.
  - Most customers don't have `online backup`.
  - Most customer don't have `device protection`.
  - Most customer don't have `tech support`.
  - Most customer don't `streaming TV`.
  - Most customer don't `Streaming Movies`.
  - Most customers have a `monthly contract`.
  - Most customer has `Electronic check` payment method.
  - Most customer `not churned`.

- ### 3.2 Reached Results between Categorical columns
  - #### Customers who left within the last month `1839`.
  - Most of them were `Female`.
  - Most of them were young not `Senior Citizen`.
  - Most of them don't have a `partner`.
  - Most of them `over 18 years`(has no dependents).
  - Most of them have `phone service`.
  - Most of them have `multiple lines`.
  - Most of them have `fiber optic` internet service(`DSL` is best service).
  - Most of them saw that the internet is `not secure`.
  - Most of them don't have `online backup`.
  - Most of them don't have `device protection`.
  - Most of them don't have `tech support`.
  - Most of them don't have `streaming TV`.
  - Most of them don't have `streaming movies`.
  - Most of them have `monthly contract`(long contract period, less customer left).
  - Most of them have `Electronic check`  payment method.
