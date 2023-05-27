
# Online Retail

This Project is based of an Online Retail store that wants to analyse major contributing factors to the revenue so they can strategically plan for next year

Note: The data for this project is taken form forage Tata Data Visualisation: Empowering Business with Effective Insights virtual experience program 

### Business Scenario

Analyzing Business Performance and Planning for Expansion.

### Introduction
As a data consultant hired by an online retail store, my role is to review the company's data and provide valuable insights to the CEO and CMO. The objective is to analyze the major contributing factors to the company's revenue and strategically plan for the upcoming year. The leadership is interested in examining both operational and marketing metrics, and they also seek guidance on areas that are performing well. Additionally, with plans for business expansion, they would like to understand the metrics based on available demographic information. 

### Dataset
The online retail data is of 2 years consist of 541910 records with 8 fields.

* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.

#### Reffer to the OnlineRetail Dataset folder to download the data
## Data Cleaning

Having clean data will ultimately increase overall productivity and allow for the highest quality information in your decision-making.

Knowing how to clean your data is advantageous for many reasons.

* It prevents you from wasting time on wobbly or even faulty
  analysis
* It prevents you from making the wrong conclusions, which would   make you look bad!

when we go the online retail data. The data consist of null values in the field customerid and description. And if we observe the data there are some return order back to the store their quantity is in negative and, Unitprice field is also have error

I have removed the null values in customerid and description field and check that the quantity should not be below 1 unit, also the Unit price should not be below $0.


## Insights and Analysis

The data is analyzed using SQL and used power BI for presenting the Insights

#### Refer SQL code and SQL Analysis folder for SQL query

#### Revenue by country

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/e17b09bd-7fc3-4263-8380-54c9faee6815)

Top 10 countries generating highest revenue, Netherlands is generating the highest revenue followed by Ireland and Germany when compare to total order and customer count Germany and Ireland have hihgest customers and order but Netherlands has highest quanity sold per product thus the revenue has highest for Netherlands.

Top 5 countries by sales
![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/0ccfc49e-013c-4865-b128-3d9ea228f73c)

Bottom 5 counties by sales
![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/49efd04d-a73a-4a16-a096-dddb704eae4a)

#### Seasonality Trend 

Total Revenue and quanity sold for each month

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/4121eb5c-3015-484c-af99-61031e08f32f)

The total number of order increases in the month of august, spetember and peakes in October. As OnlineRetail mainly sells unique all-occasion gifts and many customers are wholesalers. 

The peak in October because of most customers preffer buying the product ahead of big festivals like christmas.

#### Top customers by revenue
Top 10 customers

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/9f67a129-3ea3-429e-8d14-fad29f6ca8fa)


## Time difference between orders

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/82861f2b-bce8-4328-a27b-75a852cc8e3b)

