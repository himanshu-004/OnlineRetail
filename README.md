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

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/64f1fa0c-c510-4d82-aa34-c38da94d21eb)

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

The volume of orders experiences a noticeable upturn during the months of August and September, reaching its high point in October. This trend is particularly evident in OnlineRetail's business, where a diverse range of unique all-occasion gifts are the primary offerings, catering to a substantial number of wholesale clients.

The surge in orders during October can be attributed to a strategic consumer behavior pattern. Many customers proactively engage in purchasing products well in advance of significant festivals such as Christmas. This proactive buying behavior aligns with the desire to secure gifts and products ahead of time, thereby contributing to the pronounced peak in October.

In essence, the analysis highlights the consistent escalation of order frequency from August through September, culminating in a peak in October. This trend is intricately linked to OnlineRetail's distinct market positioning, which capitalizes on providing distinctive all-occasion gifts, and the inclination of customers, especially wholesalers, to plan their festive purchases ahead of the holiday season.

#### Top customers by revenue

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/d17eff12-815b-42c8-ad86-8fe6131bf27d)

Upon analyzing the clustered column chart, a striking insight emerges regarding customer id 14646 from the Netherlands. This particular customer stands out by contributing a substantial revenue of 280k on their own. In comparison, to other customers. while each of the other customers places an average of 21 orders.


![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/ea6c065b-c55f-4818-919a-089b5b916db0)

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/b3f0eb28-aa2f-4ca8-aea4-ae3ea99f6527)


### Time difference between orders

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/82861f2b-bce8-4328-a27b-75a852cc8e3b)

Countries such as the Netherlands and Germany stand out with a relatively lower customer count. Despite this, what's notable is that the average time difference between their orders falls within the range of 20 to 45 days. This suggests a consistent and sustained level of engagement with the platform.

What's even more intriguing is that despite having fewer customers, these countries manage to generate higher revenue. This observation underscores the significance of customer behavior and spending patterns, which seem to contribute significantly to the overall revenue, even when the customer base is comparatively smaller.

### Quantity By Region

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/b93a71b5-1bdc-44f6-af19-4c7f8bad6445)

The majority of OnlineRetail's revenue is derived from European countries, with Australia standing out as the sole continent beyond Europe where substantial product sales have occurred. This highlights the significant economic contribution of European nations to OnlineRetail's revenue stream. Additionally, Australia's notable sales activity demonstrates the company's global reach and success in penetrating markets beyond its primary focus in Europe.

### Revenue and Season trends

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/c49b49a0-2937-440c-8cf9-132bd693cc84)

Over the course of the year 2011, OnlineRetail engaged with a total of 4215 customers, predominantly consisting of wholesalers. Notably, a diverse range of 3596 unique products were offered to the customers, contributing to a significant sales volume of 5 million units. This data underscores the company's extensive customer base, product variety, and impressive sales volume achieved within the span of that year.

### Top 10's

![image](https://github.com/himanshu-004/OnlineRetail/assets/81569893/af1d3d95-d813-49cd-a3ec-19373ae145eb)

## Summary and Business Insights

In the realm of online retail, data-driven insights serve as a guiding light for strategic planning and informed decision-making. Through a thorough analysis of the online retail data, several key findings and business insights have emerged that can profoundly influence the company's expansion strategy and revenue optimization.

### Geographic Revenue Distribution

The analysis of revenue distribution across different countries has provided valuable insights into the company's market reach and potential for expansion. The Netherlands stands out as a major revenue generator, surpassing other countries in terms of revenue despite having a lower customer count. This could be attributed to the higher average spending per order by Dutch customers. On the other hand, countries like Germany and Ireland have a significant number of customers and orders, which contributes to their high revenue figures.

**Recommendation:** While continuing to nurture the existing customer bases in high-revenue countries, the company should explore strategies to tap into the potential of countries with lower revenue figures. This could involve targeted marketing campaigns, localized product offerings, or partnerships with local businesses.

### Seasonal Trends and Buying Behavior

The analysis of seasonal trends reveals a distinct surge in orders during the months leading up to significant festivals, particularly in October. This proactive buying behavior by customers, driven by the desire to secure gifts ahead of time, is a significant driver of increased revenue during these months. This trend aligns with the company's strength in providing unique all-occasion gifts.

**Recommendation:** The company can capitalize on this buying behavior by strategically planning promotions, special offers, and product releases well in advance of peak festival seasons. This approach would not only enhance customer engagement but also optimize revenue during these crucial periods.

### Customer Engagement and High-Value Customers

The identification of high-value customers, such as customer ID 14646 from the Netherlands, who contribute substantial revenue individually, highlights the importance of nurturing and retaining these customers. While these high-value customers might have lower order counts, their significant spending per order is a testament to their loyalty and trust in the brand.

**Recommendation:** Implement a customer retention strategy that includes personalized offers, loyalty programs, and exceptional customer service to maintain and strengthen relationships with high-value customers. This can lead to increased customer lifetime value and sustained revenue growth.

### Regional Insights and Market Penetration

The analysis of quantity sold by region underscores the company's dominance in the European market, with Australia standing out as a promising market outside of Europe. This indicates the potential for expanding the company's reach and diversifying revenue streams in new regions.

**Recommendation:** For international expansion, the company should conduct market research to understand local preferences, regulations, and competition. Tailoring product offerings and marketing strategies to suit the unique characteristics of each region will be key to successfully entering new markets.

### Data-Driven Decision-Making

Throughout this analysis, the power of data-driven decision-making is evident. The insights derived from the data illuminate various facets of the business, from customer behavior to seasonal trends, and from high-value customers to regional market potential. Leveraging these insights allows the company to make informed choices that align with their growth objectives.

**Recommendation:** Embrace a data-driven culture within the organization. Regularly analyze data to identify trends, opportunities, and areas for improvement. This will empower the company to adapt swiftly to changing market dynamics and seize growth opportunities.

In conclusion, this comprehensive analysis serves as a blueprint for the company's strategic planning and expansion efforts. By capitalizing on revenue drivers, understanding customer behavior, and strategically targeting new markets, the company is poised to optimize revenue, enhance customer satisfaction, and pave the way for a successful year of growth and expansion. 
