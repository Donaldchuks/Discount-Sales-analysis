# Introduction
In this project, I'm digging deep into three years worth of sales data - from 2017 to 2019. I'm examining critical metrics like discounts, sales figures, shipping costs, and returns - all the key numbers that can make or break a business. By analyzing these numbers, I aim to uncover trends, challenges, and opportunities that can inform critical business decisions.
### Problem Statement 
There was a recurrence of market sales record and you have been hired as an analyst by the company to help them gather information necessary for their next fiscal market using their retail sales record of 3 years (Historical Data) of which the recurrence happened lately.
### Objectives
This analysis aims to provide actionable insights to improve sales performance. Specifically, our objectives are:

1. To determine the effect of discounts on sales
2. To evaluate the impact of shipping costs on customer orders
3. To identify the most profitable months and years for sales
4. To decide whether to reduce discount levels in certain months
5. To analyze customer order trends and provide recommendations to increase orders
6. To investigate return rates and suggest strategies to reduce returns

### About Our Dataset
Our analysis is based on a comprehensive dataset of sales records from 2017 to 2019. The dataset includes 9 key columns:

1. Discount
2. Gross Sales
3. Net Sales
4. Month
5. Returns
6. Shipping
7. Total Orders
8. Total Sales
9. Year

**Original Dataset** [Download Link](https://docs.google.com/spreadsheets/u/0/d/1s3pC5c4fT9ni6_bkzIZwujMPiV4-Xfj2/htmlview#)
### Methodology 
This section outlines the methods used to analyze the data and answer the key questions. The analysis focused on historical sales data from 2017 to 2019, using metrics such as Gross Sales, Net Sales, Discounts, Returns, Shipping Costs, and Total Orders. Below is a brief explanation of the process for each question and what it aimed to achieve.
1. Effect of Discounts on Sales
To determine how discounts impacted sales, I calculated the Discount Rate (Total Discounts / Gross Sales * 100) and analyzed its relationship with Gross Sales to identify whether higher discounts drove sales or not. I also calculated the Profit Margin  (net sales/gross sales * 100) and analyzed its relationship with Discount Rate to see how it affected profitability. This would help us to recommend strategic discounting.
2. Evaluating Shipping Costs
I calculated the Average Shipping Cost per Order (Total Shipping Costs / Total Orders) and compared it across months and years. This helped assess whether shipping costs were reasonable and if they influenced customer orders, ensuring the company could maintain competitive shipping rates without losing customers.
3. Identifying the Best Year and Month for Sales
For this part of our analysis, I wanted to know which year and month were the most profitable for the company. To do this, I calculated the Profit Margin (net sales/gross sales * 100). By comparing net sales and profit margins, I was able to see not only how much money was coming in, but also how efficiently that revenue was being turned into profit.
This method helped identify seasonal trends and spot the months and years where sales were strongest. With this clear view of performance, the company can now focus on high-performing periods to maximize revenue and adjust strategies during slower times.
4. Deciding Whether to Reduce Discount Levels
I compared Discount Rate with both Gross Sales and Net Sales to evaluate the effectiveness of discounts. This helped identify months where high discounts did not significantly boost sales or profitability, enabling the company to adjust discount strategies.
5. Analyzing Customer Orders
I tracked Total Orders over the three years to identify trends in customer behavior. This helped determine if orders were increasing or decreasing and provided insights into how discounts and shipping costs influenced order volumes.
6. Evaluating Returns and Reducing Return Rates
To understand return patterns, I analyzed the number of returns for each month across the three years. I examined months with low return rates to see what worked well. This analysis helped recommend strategies to reduce returns and improve customer satisfaction.

The methods used aimed to provide actionable insights into sales performance, discount effectiveness, shipping costs, and return rates. By analyzing key metrics like Gross Sales, Net Sales,Discount Rate, and Total Orders, I ensured the company could make data-driven decisions to improve profitability and customer satisfaction.

### Analysis Visuals
![image](https://github.com/user-attachments/assets/6e60029a-1ce9-4db5-b982-15dfe5f8bec1)


### Question 1: Determine the Effect Discounts Had on Sales
##### Observation: 
Discounts and Sales
- Discounts effectively boost sales, especially during peak seasons like December. However, high discounts in low-demand months, such as May and October lead to no significant increase in sales.
  
Impact on Profitability
- Despite rising sales, profit margins have declined over the years: 94.04% in 2017, 92.49% in 2018, and 90.26% in 2019. This suggests that excessive discounting might be driving sales up but hurting profitability.
##### Key Insight:
While discounts can effectively stimulate sales, particularly during peak seasons, their impact on profitability varies significantly. High discounts, especially in low-demand months or when not strategically applied, can significantly erode profit margins
##### Recommendation:
1. concentrate discounts in months where they historically drive sales, such as November and December.
2. Reduce discounts in months like May and October, where they don’t significantly boost sales.
3. Instead of relying only on discounts, consider loyalty programs, personalized offers, or better customer service to keep customers coming back.
### Question 2: Should the company continue with their current shipping cost?
##### Observation
The average shipping cost per order in 2019 ($17.2) is approximately 20% higher than the average cost in 2017 ($14.3)
 Despite this, customers continued to place more orders, especially during peak months like November and December. For example:

- **November 2019:** Shipping cost per order was $17.73, but orders were high (272 orders).
- **December 2019:** Shipping cost per order was $16.68, and orders peaked at 342.

Even in months with higher shipping costs (e.g., March 2019 at $21.36), customers still placed orders, showing they are willing to pay for shipping.
##### Key Insight:
Customers are not deterred by the current shipping costs, especially during peak seasons. The company’s shipping fees are reasonable and align with market expectations.
##### Recommendation:
1. Keep Shipping Costs as They Are: There’s no need to lower shipping fees since customers are willing to pay.
2. Look for Savings in High-Cost Months: In months like March, where shipping costs are higher, try to negotiate better rates with delivery companies.
3. Offer Free Shipping Promotions: During slower months, consider free or discounted shipping to encourage more orders.
4. Conduct a competitive analysis of shipping costs to ensure the company's rates are in line with or better than industry standards
### Question 3: Which year and month they had better sales?
To get a more complete picture of sales performance, let's incorporate profit margin data into our analysis. Specifically, I want to identify the year and month with the best sales performance, considering both net sales and profit margin.

##### Observation 

Net Sales Growth
- **2017:** $91,529.50
- **2018:** $104,788.14 (14.5% increase from 2017)
- **2019:** $129,796.40 (23.8% increase from 2018)

Profit Margin Trend
- **2017:** 94.04%
- **2018:** 92.48%
- **2019:** 90.29%

While net sales increased year over year, profit margins experienced a steady decline. This means that although more was sold in 2019, a smaller percentage of revenue was retained as profit compared to previous years.

Best and Worst Performing Months
December 2019 had the highest net sales ($27,603.21), driven by a high discount rate (7.28%). However, it's essential to examine whether these discounts contributed to the declining profit margin in 2019.

March 2017 ($4,589.10) and February 2019 ($6,196.30) had the lowest sales, but March 2019 showed a significant increase, indicating potential improvements in sales strategies.

##### Key Insights
Even though 2019 had the highest net sales, the declining profit margin raises concerns. There needs to be a balance between maximizing sales and maintaining healthy profit margins.

##### Recommendation 
1. Focus on strategies that maintain or improve profit margins alongside net sales growth.
2. During peak seasons like December. Adjust discount levels to optimize profit margins without sacrificing sales volume.
3. Regularly track profit margins alongside net sales to ensure sustainable financial performance.
### Question 4: Should the Company Reduce Discount Levels in Any Month? If Yes, Which Month and Why?
##### Observation:
Yes, the company should reduce discounts in certain months where they are not effective and negatively impact profitability. Analysis reveals that high discounts do not always lead to increased profitability.
Months with High Discounts:
- **December 2019:** Despite driving high sales, the very high discount (7.28%) in December 2019 significantly impacted profit margin.
- **May 2019 and October 2018:** These months also showed a decline in profit margin despite high discounts
Months with Lower Discounts:
- **November 2017:** Demonstrated high sales with a low discount (1.01%), suggesting that lower discounts can still drive sales while maintaining healthy profit margins.
##### Key Insight:
High discounts, particularly in months where they are not essential for driving sales, can significantly affect profit margins.
##### Recommendation
1. Based on the analysis, consider reducing discount levels in May and October and Given the significant impact of the high discount in December 2019 on profit margin, consider a slight reduction in discount levels for December
### Question 5: Are the customers' orders going higher or lower? And what should be done to increase the customer order for 2019?
##### Observation
Customer orders have been increasing over the years:

**2017:** 836 orders

**2018:** 1,141 orders (36.4% increase from 2017)

**2019:** 1,520 orders (33.2% increase from 2018)

However, the growth rate slowed slightly in 2019. Orders were highest in November (272 orders) and December (342 orders) but lowest in February (63 orders) and June (85 orders).
##### Key Insight:
While orders are growing, there is potential to boost sales further, especially in low-order months like February and June.
##### Recommendation:
1. Run special promotions or events in February and June to attract more customers.
2. Reserve significant discounts  for months where they’ll have the most impact, like November.
3. Leverage social media, email marketing, and strategic partnerships to attract more customers during slower months.
4. Create a loyalty program to encourage repeat purchases
### Question 6: There might be too many returns in 2017 and 2018, if there is, what are the Observation
##### Observation
In 2017, March had the highest returns ($1,017), while April had no returns. In 2018, June had the highest returns ($1,507), while September had no returns. The data also showed that returns were more consistent in 2017, with most months having returns below $500. In contrast, 2018 had more extreme variations, with some months having very high returns.

##### Key Insight
The analysis revealed that returns are not evenly distributed throughout the year. Certain months experience significantly higher returns, indicating potential issues with product quality, shipping, or customer satisfaction.

##### Recommendation
To reduce the return rate, I suggest:

1. understand why there were so many returns in months like March 2017 and June 2018. What went wrong, and how can we prevent it from happening again?
2. Analyze what's working well in April and November and apply those strategies to other months.
3. Provide clear and detailed product descriptions to reduce confusion.
4. Collect customer feedback to pinpoint and address satisfaction issues.


### Conclusion
After digging into three years of sales data (2017–2019), I have uncovered some really useful insights that can help make smarter decisions and grow in business. Let’s break it down in simple terms. 

### What We Learned
1. Discounts Work, But Be Careful
   
Discounts are great for boosting sales, especially during busy times like November and December (think holiday shopping). But giving too many discounts in slower months, like May or October, can hurt profits. The trick is to use discounts wisely—focus on the times when they really drive sales.

2. Shipping Costs Are Okay, But Let’s Watch Them
   
Customers don’t seem to mind the current shipping costs, even when they go up a bit. But in months where shipping costs are really high (like March), we might want to negotiate better rates with delivery companies. Also, offering free or cheaper shipping during slower months could help bring in more orders.

3. Sales Are Seasonal—Plan for It
   
Sales are strongest at the end of the year (November and December), so let’s make sure we’re ready to take full advantage of those peak times. On the flip side, we need to find ways to boost sales during slow months, like February and June.

4. Customers Are Ordering More - Let’s Keep It Going
   
Orders have been growing every year, which is great! But the growth slowed a bit in 2019. To keep things moving, we can run special promotions or events during slower months and use marketing (like social media or email campaigns) to attract more customers.

5. Too Many Returns? Let’s Fix That
   
Some months, like March 2017 and June 2018, had a lot of returns. This could be due to issues like product quality, shipping mistakes, or customers not getting what they expected. By improving product descriptions, checking quality before shipping, and asking customers for feedback, we can reduce returns and keep more of our profits.

### What To Do Next
- Use Discounts Smarter: Save big discounts for busy times like November and December, and cut back on discounts in slower months.
- Keep Shipping Costs in Check: Customers are okay with the current costs, but let’s look for ways to save money in high-cost months and offer free shipping deals during slower times.
- Focus on Peak Seasons: Double down on marketing and inventory during November and December to maximize sales.
- Boost Slow Months: Run promotions or events in slower months like February and June to bring in more orders.
- Reduce Returns: Figure out why returns are high in certain months and fix the issues—whether it’s better product descriptions, quality checks, or clearer policies.
- Keep Customers Happy: Start a loyalty program or send personalized offers to encourage repeat business.

### Final Thoughts
The big takeaway is, there’s a lot of opportunities to grow sales and improve profits, but there's also a need to be strategic. By focusing on the right times to offer discounts, keeping shipping costs reasonable, and fixing the return problem, we can set up for success. keep an eye on the numbers, listen to customers, and make smart decisions to keep the business growing.

