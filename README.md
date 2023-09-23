# Customer_behavior_analysis
In this Project, We created the webapp using streamlit which will deliver the KPI's, basic Dashboard and Marketing optimization strategy.
## Data description
CustomerID: Unique id for each customer.  
VisitDate: Dates on which customer made a purchase.  
TotalSpend: Total amount spend by the customer.  
ProductCategory: Product Category.  
We created a Dummy dataset of 1000 rows using Faker and used this data to create a dashboad.

## Observation
These are  the observation based on the default dataset which we have created using Faker, If users choose different datasets then results will vary.

* The average spending per customer is: 984.75.  
**Top 10 customer with the maximum spending**
  ![most_spending_customer](https://github.com/ad709kr/Customer_behavior_analysis/assets/102454963/4b3367ed-cd9f-4fe3-abb6-392945449e2a)
**Top 10 most frequent customer**
![most_frequent_customer](https://github.com/ad709kr/Customer_behavior_analysis/assets/102454963/d00bdd45-2cae-4454-91c5-8bbb6e15db7c)
**Product Category:** Most Popular Product Category is Healthcare, with total number of sales: 108
**Product Category vs total sales**
  ![product_category_vs_total_sales](https://github.com/ad709kr/Customer_behavior_analysis/assets/102454963/28513f98-83bd-4126-845c-41fc265273e3)

**monthly revenue growth**
* Maximum Revenue Month: 2022-10

* Minimum Revenue Month: 2022-09

* Average Monthly Revenue: 75749.92

![monthly_revenue_growth](https://github.com/ad709kr/Customer_behavior_analysis/assets/102454963/f9787b7a-a811-460c-a693-09a1c50dd3a4)

## How to Use the app
* step 1 : To clone the repository
* step 2 : create an environment (streamlit) and install all packages from requirement.txt
* step3 : Open terminal and write command 'streamlit run app.py'
* After step3 a streamlit dashboard will open where you have two options: 1. Upload Custom dataset or 2. Use Default Dataset.
* If you choose option 1, you will get the option to upload your dataset. (make sure your dataset have same feature name)
* If you choose 2 options, the dashboards with kpi's will be shown.
* And At the end, you have to choose at what spending category you belong to and based on that you will get suitable discounts.
