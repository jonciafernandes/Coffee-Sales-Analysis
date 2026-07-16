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

The dashboard was developed entirely in Microsoft Excel, utilizing XLOOKUP, INDEX, and MATCH functions to consolidate data from multiple worksheets into a single dataset. PivotTables, PivotCharts, Slicers and Timelines were incorporated in building interactive business intelligence dashboard that supports dynamic filtering and data-driven decision-making.

### Data Structure and Initial Checks
The analysis was conducted using three related datasets containing order transactions, customer information, and product details. Together, these datasets provide a comprehensive view of coffee sales, customer purchasing behaviour, and product offerings between 2 January 2019 and 19 August 2022.

| Orders | Customers | Products |
|:------:|:---------:|:--------:|
| <img src="https://github.com/user-attachments/assets/19967c96-cb68-4b47-9aee-a0f041ffc2fe" width="220"> | <img src="https://github.com/user-attachments/assets/39a688aa-c4e0-43ff-96dc-de6fd237bdfb" width="220"> | <img src="https://github.com/user-attachments/assets/ae07eb58-5277-475d-b737-dcbd892aaaa4" width="220"> |

Prior to building the dashboard, the datasets were reviewed for consistency and completeness. Data from the three worksheets was consolidated into a single analysis table using XLOOKUP, INDEX, and MATCH functions to retrieve customer and product information based on their respective IDs. Additional calculated fields, including Sales, were created to support the analysis.

The consolidated dataset was then used to create PivotTables, PivotCharts, Slicers, and a Timeline, enabling the development of an interactive Excel dashboard for exploring sales performance, customer behaviour, and product trends.

### Executive Summary
The analysis of coffee sales from 2 January 2019 to 19 August 2022 revealed valuable insights into sales performance, product profitability, customer purchasing behaviour, and market trends. While sales fluctuated throughout the reporting period, the business experienced several strong sales peaks, indicating periods of increased customer demand.

<img width="300" height="150" alt="image" src="https://github.com/user-attachments/assets/9b360882-469d-4bef-a89a-50d783a5dd5f" />

Among the four coffee varieties, Excyllsa generated the highest total sales, while Librica emerged as the most profitable product overall. The 2.5 kg package consistently produced the highest profit across all coffee types, highlighting the strong contribution of larger pack sizes to overall profitability. Although Arabica recorded the highest number of units sold, it did not generate the highest revenue or profit, demonstrating that higher sales volume does not always translate into greater profitability.

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/7433882b-ebc0-4826-bbd4-b29acacc1a1d" />

The United States accounted for the largest share of total sales, significantly outperforming Ireland and the United Kingdom. Customer purchasing patterns also varied by Loyalty Card status and Roast Type, suggesting opportunities for targeted marketing and customer retention initiatives. Based on these findings, the business should focus on promoting its most profitable products while expanding loyalty program participation to encourage repeat purchases and long-term customer value.

