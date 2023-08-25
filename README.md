# Collection-Performance-Analysis
Finance Excel, R, Power BI

A collection performance analysis aims to assess the effectiveness of the company's collection strategies and processes. 
Specifically, the analysis aims to identify areas where the company can improve its collections processes, reduce its default rates, 
and increase its recovery of outstanding debts. By analyzing key metrics such as the total number of customers, total transactions, total balance, and total amount.

## Analysis Pipeline

**•	Data Cleaning** 

Used Excel and R for data cleaning. In the transaction Table, all Transaction dates for interest payments were recorded as text/characters. Importing such data to Power BI would show an error. Decided to use R with the use of the Lubridate library to convert the column to a datatype that will allow any date functions to be carried out. 

**•	Data Joining**

Then joined the transaction table in Excel,

**•	Data Presentation** 

Changed columns to appropriate data types that fit the aim of the analysis and performed necessary manipulation.Carried out data visualization using Power BI to create a Collection Performance Dashboard.

![Dashboard](https://github.com/rajikudusadewale/Collection-Performance-Analysis/blob/main/Dashboard%20screenshot.jpg)

[**You can interact with the dashboard here**](https://app.powerbi.com/view?r=eyJrIjoiYjdmNjY5M2EtMzA5MS00ZjdkLTkwYmEtNmViOTMzZjkzZWFlIiwidCI6IjM3NzY1MTAyLWQwZjgtNDJmYi05NTQ3LTY1ZTAwMTllZDk1ZiJ9)
### Trends and Insights

	The line chart showing the balance over time indicates that there is an up-and-down trend in the balance for the top 5 product types. The fluctuating trend in the balance for the top 5 product types indicates that the collection strategy is average.

	The line chart showing the default date count and date of default indicates that there is an increase in default rate, mostly from December to January.

	The Bar chart shows that the most used product is the Master card with 20% of overall customers, and it has transacted the most. 

	The doughnut chart shows the total number of Repayment and Interest transactions done, which are 37752 and 37870, respectively. 

	The product type with the highest number of defaults also has the highest number of customers.

	But the right chart shows that the product type with the highest number of defaults and customers differs from the product with the highest default rate.

	Visa product has the highest default rate percentage compared to the master card, with a higher number of customers and default count.

	Most customers enter arrears after missing a repayment on their debt within the years. There has been an increase in the trend of debt counts over the years.

	The left chart shows the top 5 customer IDs with the highest outstanding debts in 2021.

	While the right chart shows the customer IDs with the lowest outstanding debts

	The bar charts for the top 5 customers with the highest and lowest outstanding debts provide insight into individual customer behaviour.

	The Total Number of Customers has been increasing gradually over the years.

	The Total Transactions have increased over the years, but more data is still needed for validation.

	The Total Balance has been fluctuating over the years.

	The Total Amount has been fluctuating over the years.

### Patterns

	The Total Balance and Total Amount have similar patterns, indicating a relationship between them.

	There is a fluctuating trend in the balance for the top 5 product types.

	A majority of customers are using one specific product.

### Key Areas of Interest

**•	Default rates** 

The clustered column chart showing the number of customers that use each product with their Date of Default count is an important metric to track. If the default count increases over time, it may indicate that the collection strategy is ineffective, and further action may be necessary.

**•	Product performance**

The line chart showing the balance over time, broken down by the top 5 product types, is useful for identifying balance trends by product. If there are any significant differences in performance between products, it may indicate a need to adjust collection strategies or marketing efforts.

**•	Repayment vs Interest** 
The doughnut chart showing the percentage of transaction type (either repayment or interest) is an important metric to track. If the proportion of interest payments increases over time, it may indicate that customers are struggling to make payments, and further action may be necessary.

**•	Top customers** 

The bar charts showing the 5 top customers with the highest and lowest outstanding debts are useful for identifying customers needing additional attention. It is important to ensure that high-risk customers receive the support they need to avoid defaulting on their loans.

•	Overall, these metrics can provide valuable insights into the performance of the collection strategy and identify areas that may require further attention or improvement.

#### Conclusion

The collection strategy is average. Most customers enter arrears after missing a repayment on their debt within the years. The high concentration of customers using one specific product indicates an opportunity to expand the product portfolio and diversify the customer base. Both Repayments and interest transactions take up 50% each of all the total transactions done for the years. The variation in transaction amounts and default rate percentage by product type requires further investigation to determine the underlying reasons for the differences. 

#### Recommendations


•	Optimizing the current collection strategy will give way to an effective strategy for reducing the outstanding debt owed by customers. 

•	Encourage customers to make repayments on time to reduce the number of customers entering arrears after missing a repayment on their debt. 

•	The product team should explore opportunities to expand the portfolio to attract new customers and reduce reliance on a single product.

•	Further analysis should be conducted to understand the drivers of variation in transaction amounts and default rate percentage by product type.

•	The product type with the highest defaults requires closer monitoring and intervention.

•	The concentration of defaults around the end of the year suggests that seasonal factors may contribute to financial difficulties for customers, which should be considered in collection strategies.

•	The transaction amounts for each product type can inform marketing and promotional strategies to encourage more spending on loans with lower transaction amounts.

