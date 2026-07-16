# Coffee Sales Analysis
### Project Background
Founded in 2018, Brew Haven Coffee is a fictional specialty coffee retailer that sells premium coffee beans through its online store. The company offers four coffee varieties, each available in multiple roast levels (Light, Medium, and Dark) and four package sizes to cater to a wide range of customer preferences. To encourage repeat purchases and strengthen customer relationships, the business also operates a Loyalty Card program.

Between 2 January 2019 and 19 August 2022, Brew Haven recorded customer orders from customers across the United States, Ireland, and the United Kingdom. While the business had accumulated valuable sales, customer, and product information, the data was spread across multiple tables, making it difficult to monitor business performance and identify meaningful trends.

This project analyzes sales performance, customer purchasing behaviour, and product trends by integrating order, customer, and product data into a single interactive Excel dashboard.

Insights and analysis are provided on the following key areas:

**Sales Performance Analysis** - Evaluation of total sales over time to identify revenue trends, seasonal fluctuations, and periods of strong or weak business performance.

**Geographic Sales Analysis** - Assessment of sales generated across the United States, Ireland, and the United Kingdom to determine the company's strongest-performing markets.

**Customer Analysis** - Identification of the highest-value customers based on total sales, enabling the business to recognize its most valuable customer relationships.

**Product Analysis** - Analysis of coffee sales across different coffee varieties, roast levels, and package sizes to understand customer preferences and product performance.

**Loyalty Program Analysis** - Comparison of purchasing behaviour between Loyalty Card members and non-members to evaluate customer engagement and support retention strategies.

The [dashboard](https://github.com/jonciafernandes/Coffee-Sales-Analysis/blob/main/CoffeeSalesDashboard.png) was developed entirely in Microsoft [Excel](https://github.com/jonciafernandes/Coffee-Sales-Analysis/blob/main/coffeeOrdersDataAnalyzed.xlsx), utilizing XLOOKUP, INDEX, and MATCH functions to consolidate data from multiple worksheets into a single dataset. PivotTables, PivotCharts, Slicers and Timelines were incorporated in building interactive business intelligence dashboard that supports dynamic filtering and data-driven decision-making.

### Data Structure and Initial Checks
The analysis was conducted using three related datasets containing order transactions, customer information, and product details. Together, these datasets provide a comprehensive view of coffee sales, customer purchasing behaviour, and product offerings between 2 January 2019 and 19 August 2022.

| Orders | Customers | Products |
|:------:|:---------:|:--------:|
| <img src="https://github.com/user-attachments/assets/19967c96-cb68-4b47-9aee-a0f041ffc2fe" width="220"> | <img src="https://github.com/user-attachments/assets/39a688aa-c4e0-43ff-96dc-de6fd237bdfb" width="220"> | <img src="https://github.com/user-attachments/assets/ae07eb58-5277-475d-b737-dcbd892aaaa4" width="220"> |

Prior to building the dashboard, the datasets were reviewed for consistency and completeness. Data from the three worksheets was consolidated into a single analysis table using XLOOKUP, INDEX, and MATCH functions to retrieve customer and product information based on their respective IDs. Additional calculated fields, including Sales, were created to support the analysis.

The consolidated dataset was then used to create PivotTables, PivotCharts, Slicers, and a Timeline, enabling the development of an interactive Excel dashboard for exploring sales performance, customer behaviour, and product trends.

### Executive Summary
The analysis of coffee sales from 2 January 2019 to 19 August 2022 revealed valuable insights into sales performance, product profitability, customer purchasing behaviour, and market trends. While sales fluctuated throughout the reporting period, the business experienced several strong sales peaks, indicating periods of increased customer demand.

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/9b360882-469d-4bef-a89a-50d783a5dd5f" />

Among the four coffee varieties, Excyllsa generated the highest total sales, while Librica emerged as the most profitable product overall. The 2.5 kg package consistently produced the highest profit across all coffee types, highlighting the strong contribution of larger pack sizes to overall profitability. Although Arabica recorded the highest number of units sold, it did not generate the highest revenue or profit, demonstrating that higher sales volume does not always translate into greater profitability.

<img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/7433882b-ebc0-4826-bbd4-b29acacc1a1d" />

The United States accounted for the largest share of total sales, significantly outperforming Ireland and the United Kingdom. Customer purchasing patterns also varied by Loyalty Card status and Roast Type, suggesting opportunities for targeted marketing and customer retention initiatives. Based on these findings, the business should focus on promoting its most profitable products while expanding loyalty program participation to encourage repeat purchases and long-term customer value.

### Deep Dive into Insights 
**Sales Performance Over Time**: Coffee sales fluctuated throughout the reporting period, with recurring peaks and dips across the four years of analysis. Notable sales peaks were observed in April 2019, February 2020, and September and November 2021, indicating periods of increased customer demand. Conversely, sales declined during May 2019, August 2020, and February 2022, suggesting seasonal fluctuations or reduced purchasing activity. Despite these variations, overall sales remained relatively consistent throughout the analysis period.

**Coffee Type Performance**: All four coffee varieties contributed relatively evenly to total sales, although Excyllsa generated the highest overall revenue, followed closely by Librica and Arabica, while Robusta recorded the lowest sales. When segmented by Loyalty Card status and Roast Type, customer preferences varied across coffee varieties, indicating that purchasing behaviour differs among customer groups rather than being driven by a single dominant product.

**Sales Volume Analysis**: Although Arabica recorded the highest number of units sold, it did not generate the highest sales or profit. This suggests that sales volume alone is not a reliable indicator of business performance, as product pricing and package size significantly influence revenue and profitability. Overall, the difference in units sold across the four coffee varieties was relatively small, reflecting balanced customer demand.

**Profitability and Package Size**: Package size had a significant impact on profitability. The 2.5 kg package consistently generated the highest profit across all coffee varieties, while the 0.2 kg package contributed the least. Librica emerged as the most profitable coffee type overall, with particularly strong performance in larger package sizes. These findings indicate that encouraging customers to purchase larger pack sizes could substantially improve overall profitability.

**Pricing Trends**: Average selling prices remained relatively stable throughout the analysis period for the 0.2 kg package, whereas larger package sizes—particularly 2.5 kg and 1 kg—experienced greater price fluctuations over time. Despite these fluctuations, larger package sizes continued to generate the highest profits, demonstrating their importance to the business's revenue strategy.

**Geographic Sales Performance**: The United States accounted for the majority of total sales, significantly outperforming both Ireland and the United Kingdom. This indicates that the United States represents the company's primary market, while the remaining countries present opportunities for future market expansion and targeted promotional campaigns.

**Customer Loyalty Insights**: Customer purchasing behaviour differed between Loyalty Card holders and non-members. While sales and profit rankings varied across coffee varieties, customers enrolled in the loyalty program consistently contributed a substantial share of overall revenue. The analysis also identified several high-value customers who were not enrolled in the loyalty program, highlighting an opportunity to improve customer retention through targeted loyalty initiatives.

### Recommendations
Based on the analysis, the following recommendations are proposed to improve sales performance, profitability, and customer retention:

**1. Promote High-Profit Products and Larger Package Sizes**: The 2.5 kg package consistently generated the highest profit across all coffee varieties, while Librica and Excyllsa emerged as the strongest-performing products in terms of profitability. Marketing campaigns, product bundles, and promotional offers should prioritize these high-margin products to maximize overall revenue.

**2. Strengthen the Loyalty Card Program**: The analysis indicates that Loyalty Card members contribute significantly to overall sales. The business should encourage high-value customers who are not currently enrolled to join the loyalty program by offering exclusive discounts, reward points, or personalized promotions. This can help increase repeat purchases, customer retention, and long-term customer value.

**3. Expand Sales in Underperforming Markets**: The United States accounted for the majority of total sales, while Ireland and the United Kingdom contributed comparatively lower revenue. Targeted regional marketing campaigns, localized promotions, and market-specific product offerings could help increase brand awareness and drive sales growth in these underperforming markets.

**4. Optimize Product Portfolio Based on Profitability**: Although Arabica recorded the highest sales volume, it did not generate the highest revenue or profit. Business decisions should therefore prioritize profitability rather than sales volume alone by promoting products that deliver stronger financial returns, such as Librica and Excyllsa, particularly in larger package sizes.

**5. Monitor Seasonal Sales Trends for Better Planning**: Sales exhibited recurring peaks and dips throughout the analysis period, suggesting seasonal purchasing patterns. Forecasting demand using historical sales trends can help optimize inventory planning, staffing, and promotional activities during periods of high demand while minimizing stock shortages and excess inventory during slower months.

**6. Maintain Competitive Pricing for Larger Package Sizes**: While average prices for larger package sizes fluctuated over time, they continued to generate the highest profits. Regularly reviewing pricing strategies and ensuring that larger packages provide clear value to customers can help maintain profitability while encouraging higher-value purchases.
