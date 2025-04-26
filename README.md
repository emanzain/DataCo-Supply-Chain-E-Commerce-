## Data-co-supply-chain-E-commerce
# Overview :

A Power BI dashboard designed to analyze and optimize the purchasing and order fulfillment process. It provides a comprehensive view of customer demand, order distribution, regional market dynamics, and shipping efficiency. The dashboard uses historical data to uncover trends in product pricing, discounts, profits, and customer behavior. Ideal for supply chain analysts and business managers to monitor operational performance, understand market demands, and improve decision-making.

# Key Features:

Order Lifecycle Analysis: Tracks the customer journey from placing an order to fulfillment, highlighting how customer requests are directed to the appropriate market within the order region, which then processes and ships the orders.

Sales & Profit Insights: Examines total sales, profit margins, and discount impact. Includes before-and-after outlier analysis to ensure data accuracy and highlight profit potential when discount variance is managed.

Product & Pricing Trends: Compares product price distributions, highlighting differences between average and median prices. Shows how discounts influence sales volumes and how price adjustments impact overall profitability.

Correlation Analytics: Measures the relationship between discounts, sales, and profit, helping identify optimal discount strategies. Strong positive correlation between discount and sales volume reveals how promotions drive demand.

Performance Indicators: Visual elements showcase average and median sales, profit values, product pricing trends, and correlation coefficients to guide strategic pricing, inventory, and marketing decisions.

![Screenshot 2025-04-26 205902](https://github.com/user-attachments/assets/89907f37-9416-46f6-b98b-b4b073142d73)



Order Placement: The customer initiates the process by placing an order through the e-commerce platform.

Order Routing: The order is directed to the relevant customer account or department responsible for processing it.

Market Allocation: The order is assigned to the specific market or region that handles its fulfillment based on predefined criteria (e.g., location, availability).

Shipping Execution: The order proceeds to the shipping phase, where it is prepared, dispatched, and delivered to the end consumer.

![Screenshot 2025-04-26 205924](https://github.com/user-attachments/assets/6112fcb4-5979-4899-8ee7-92c3ff892a82)


Overview: Dataco processed 66K orders from 2015 to 2018
Customer and Market Scope: The data covers 21K customers across 5 markets (e.g., Africa, Europe) and 164 countries, with orders categorized into 11 departments and 51 product categories.

Geographic Reach: Operations span global regions including North America, Asia, and Australia, with key markets like LATAM and Pacific Asia highlighted.

Annual Order Trends: Order volumes remained steady at ~21K–22K annually from 2015 to 2018, indicating consistent demand over the period.

![Screenshot 2025-04-26 205948](https://github.com/user-attachments/assets/212665fe-fc7d-4c6b-a5ad-2397a36138c5)


Total Sales Overview:
The total sales amount to 35.214 million, with the Fan Shop department leading sales at 16.39 million, followed by Apparel and Golf.

Sales Trend Over Years:
Sales remained stable around 11.8 million from 2015 to 2016, slightly dipped to 11.3 million in 2017, and then dropped sharply to 0.3 million in 2018.

Top-Selling Products:
The best-selling product is Field & Stream Sportsman 16 Gun Fire Safe, followed by Diamondback Women's Bike and Nike Men’s Shoes, based on descending sales volume.

Market and Parameter Filters:
The dashboard allows users to filter data by Market regions (Africa, Europe, LATAM, etc.) and Sales & Profit Parameters (Total Sales, Profit, Margin, Orders).

![Screenshot 2025-04-26 210001](https://github.com/user-attachments/assets/888c2889-993c-4c51-8b06-80400e4d9fcd)


Customer Retention & Segments

Overall customer retention rate is 59.16% (20.65K customers).

Customer segments: Consumers (34K orders), Corporate (20K), Home Office (12K).

Puerto Rico accounts for 38.41% of orders (7.93K), while the U.S. leads with 61.59% (12.72K).

Market Performance

Key markets: LATAM, USCA, Africa, Europe, and Pacific.

Metrics tracked: Total Sales, Profit, Profit Margin, and Order Volume.

Annual Trends

Retention rates fluctuated yearly: 92.16% (2015), 92.00% (2016), dropping to 53.07% (2017).

Example customer "Aaron Berger" (Consumer segment) placed 66K orders with an average order value (ACV) of $559.45.

Payment & Shipping

Payment methods: Debit, Transfer, Payment, and Cash.

Shipped vs. canceled shipments shown, with shipped orders peaking at 25K.

![Screenshot 2025-04-26 212419](https://github.com/user-attachments/assets/e1cd50f3-2fb3-440f-bb3f-98472df0ab09)


Market Overview: 63K shipments were made with an order fulfillment rate of 45.2%, and about 3K orders were canceled. The products sold and regional coverage both reached 100%.

Market and Regional Insights: Europe remains the highest in total orders (18.56K), followed by Pacific Asia (17.58K) and LATAM (17.18K).

Sales Trends Over Years: From 2015 to 2018, Europe and LATAM showed consistently strong sales, with the bubble chart indicating larger volumes compared to other regions.

Order Timeliness: 54.82% of orders were delivered on time, while 45.18% were late. Western Europe led sales percentage among all regions.

![Screenshot 2025-04-26 210032](https://github.com/user-attachments/assets/598529f0-79eb-4742-813e-8f513d9b2c95)


Shipping Performance Overview

Standard Class is most used (59.81% of shipments)

Delivery reliability: 75.99% on-time, 24.01% early

Average delay time is consistently 2 days across all regions

Regional Delivery Metrics

Africa shows highest on-time delivery (96%)

Canada has lowest on-time rate (91%) and highest cancellations (8.62%)

Pacific Asia shows perfect 100% delivery rate (though sample size is small)

Shipping Mode Distribution

Standard Class dominates (39.3K shipments)

Same Day is least used (3.6K shipments, 5.43%)

First Class (15.33%) and Second Class (19.43%) show moderate usage

Cancellation Patterns

Central/South America have highest cancellation rates (6.58%)

Europe maintains consistent 95-97% delivery rates

US regions show 94-96% delivery rates with West USA having most cancellations (5.53%)

The data reveals Standard Class as the preferred shipping method with generally reliable 2-day delivery times across regions, though cancellation rates vary significantly by location.

![Screenshot 2025-04-26 210046](https://github.com/user-attachments/assets/872d65f3-2327-4a3a-8493-bc7da183ea0f)


Profit Segmentation Analysis

Customers are categorized into five profit segments: High Loss (≤ -2000), Moderate Loss (-2000 to 0), Neutral (0-500), Profitable (500-1500), and High-Value (1500-2442).

Example: Customer #2641 ranks #1 in profit (High-Value), while #791 shows Moderate Loss.

Top-Performing Categories
Computers has the highest total sales ($6.87M) but lower profit margins due to high costs.
Key Insights

High-value customers (e.g., #2641, #1657) significantly boost profitability.

Categories like Electronics and Garden show lower sales volumes but stable margins.

  ![Screenshot 2025-04-26 205846](https://github.com/user-attachments/assets/b02b4e06-356c-446c-b08c-48398971c5ff)


The analysis shows that removing outliers from sales data has minimal impact on the average, while profit increases significantly when discount variance is adjusted.

Discounts play a key role in boosting sales, as evidenced by the strong positive correlation (0.81) between discounts and sales, and the alignment of median and average prices post-discount.

Profitability improves without outliers, with the average profit rising from 21.97 to 38.58, suggesting that strategic discounting can enhance financial outcomes.

The data reflects a diverse product price range, where higher discounts on premium items drive sales and improve the correlation between sales and profit (0.58).

![Screenshot 2025-04-26 210106](https://github.com/user-attachments/assets/1c369aad-0c56-4914-92d8-980cc30ede6a)


Data Processing and Calculations

This Power BI dashboard leverages several key tools and technologies to perform data transformations and calculations:

Power Query: Used for data importation and transformation, Power Query enables the cleaning, shaping, and loading of data from various sources into the Power BI environment. This process ensures that the data is in the correct format for analysis.

DAX (Data Analysis Expressions): DAX is utilized for creating custom calculations and measures within the dashboard. It allows for advanced data modeling and enables the creation of dynamic calculations that respond to user interactions and filter selections.

Data Modeling: The relationships between different data tables are established to create a comprehensive data model. This ensures accurate insights and visualizations throughout the dashboard.











