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

* Top 10 countries generating highest revenue
Netherlands is generating the highest revenue followed by Ireland and Germany when compare to total order and customer count Germany and Ireland have hihgest customers and order but Netherlands has highest quanity sold per product thus the revenue has highest for Netherlands.

#### Top 5 countries by sales

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/0ccfc49e-013c-4865-b128-3d9ea228f73c)

When examining the stacked bar chart, it becomes evident that the Netherlands holds the highest number of sales in comparison to the other countries displayed. Upon comparing the statistics with Germany, it is noticeable that the total number of orders and customer count in the Netherlands are fewer. However, a significant observation emerges when analyzing the average spending per order. In the Netherlands, each customer spends an average of 3,036.66 per order, which starkly contrasts with Germany's average spending of 500.80 per order.

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/9894abc3-f8da-4bd3-ba34-fd905218645c)

To sum up, while the Netherlands may have fewer orders and customers than Germany, the remarkable disparity in the average spending per order underscores the pronounced economic contribution of the Netherlands to the overall sales figures.

#### Bottom 5 counties by sales

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/49efd04d-a73a-4a16-a096-dddb704eae4a)

Upon examination of the data, it becomes evident that the Bottom 5 countries with the lowest sales are predominantly situated in the Middle East or North America. These regions show limited engagement with the OnlineRetail platform, with most of these countries having either only 1 customer or fewer than 5 customers.

While OnlineRetail enjoys a substantial presence in Europe, it's worth noting that certain countries within the continent, such as the Czech Republic, Lithuania, and Malta, demonstrate a comparably lower presence of OnlineRetail stores.

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/5315258e-072c-4df2-abdb-d5c07ddbd419)

In summary, the statistics reveal a notable discrepancy in customer engagement across different regions, with the Middle East and North America showing minimal OnlineRetail activity, and certain European countries displaying relatively modest online retail participation.

#### Seasonality Trend 

Total Revenue and quanity sold for each month

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/4121eb5c-3015-484c-af99-61031e08f32f)

The total number of order increases in the month of august, spetember and peakes in October. As OnlineRetail mainly sells unique all-occasion gifts and many customers are wholesalers. 

The peak in October because of most customers preffer buying the product ahead of big festivals like christmas.

#### Top customers by revenue
Top 10 customers

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/9f67a129-3ea3-429e-8d14-fad29f6ca8fa)


### Time difference between orders

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/82861f2b-bce8-4328-a27b-75a852cc8e3b)

Countries like Netherlands and Germany have lesser number of customer and the average time difference of their order is between 20 to 45 days but the revenue generated by this countries are higher. Although the customer count is less

### Quantity By Region

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/b93a71b5-1bdc-44f6-af19-4c7f8bad6445)

Most of the revenue of OnlineRetail is generated through European countries other than Europe Austrial is the only countinent where OnlineRetail have sold most of its products.

### Revenue and Season trends

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/c49b49a0-2937-440c-8cf9-132bd693cc84)

Throught out the year in 2011 the OnlineRetail have 4215 customer where most of the customer are wholesalers there were total of 3596 unique products and 5 million quality were sold

### Top 10's

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/af1d3d95-d813-49cd-a3ec-19373ae145eb)
