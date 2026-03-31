## **🏢 Company Overview – Freedom Sales Pvt. Ltd.**
Freedom Sales Pvt. Ltd. is a dynamic marketing and distribution company specializing in a diverse portfolio of consumer products across multiple categories. The company focuses on delivering high-quality products through an extensive network of retail outlets, modern trade channels, and strategic partnerships.
For this analysis, the focus is specifically on the chocolate segment, one of the company’s key revenue-generating categories. The study evaluates sales performance, customer behaviour, product trends, and profitability within the chocolate portfolio to uncover actionable insights and support strategic decision-making.

## **Business Problem**
Freedom Pvt. Ltd. is experiencing stagnant revenue growth despite stable sales and a healthy profit margin. The company lacks visibility into regional performance, customer behaviour, product demand, and the impact of discounts on profitability.
## **Objective**
To build an interactive Power BI dashboard that analyses sales, customer segments, product performance, and discount strategies to identify growth opportunities, optimize profitability, and support data-driven decision-making.

## **🛢 Dataset Details**
- **Source:** Kaggle  
- **Dataset Name:** Chocolates Sales Dataset 2023-2024
- **Dataset Description:** The dataset used for this analysis contains transactional, regional, Product, and customer-level data for the chocolate sales segment of Freedom Sales Pvt. Ltd. for the years 2023–2024.
Files & Key Data Fields: 
- Customers: customer id, age, gender, loyalty member, join date
- Calendar: date	year, month, day, day of week,	week number, Month Name
- Product: Product id, Product name, brand, category, cocoa percentage, weight
- Stores: store id, store name, city, country, store type
- Sales: order id, order date, product id, store id, customer id, quantity, unit price, discount, revenue, cost, profit 
## **🧹️ Data Processing & Transformation**
-	Cleaned missing and duplicate records 
-	Standardized the data for consistency
-	Filtered the data  from fact sales table( having two additional product id that was not present in product table) to resolve blank issue in visuals for products analysis.
Data structuring & Modeling
-	Created staging layers to model the data & disable the load for raw data layer. 
-	Modeled the data into a star schema with fact and dimension tables for efficient analysis in Power BI.
-	Created calculated columns (Age Groups), new category table for showing revenue to net profit bridge.
-	Extracted month name & day name from date field and mark the calendar table as date table for time-based analysis
-	Built measures in Power BI (DAX) for KPIs 
## **🛠️ Tools Used**
- **Data Processing & Transformation:** Power Query Editor
- **Data Visualization & Analysis:** Power BI, DAX
## **📑 Report contents**
This repository contains a PDF version of the Power BI report hosted on the Power BI Service, along with its underlying data model. A screenshot of the data model and the report PDF are provided below for a quick preview. 
- [Dashboard PDF](https://github.com/savita-sharmaa/Chocolate-Sales-Analysis/blob/main/Choco_Sales%20Analysis.pdf)
- [Data Model](https://github.com/savita-sharmaa/Chocolate-Sales-Analysis/blob/main/Chocolate%20Sales-%20Data%20Model.png)
- [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGE2OTlhY2YtOGZkYS00ZGFjLWE3NDktNWViMTQzYzExMTYxIiwidCI6IjU3ZGZkMTU2LWVmYzMtNDE3MS05MDAwLWYxYTQwYjljMGE5NiJ9)

## **📊 Insights**  

Revenue growth remained largely stagnant between 2023 and 2024, with consistent customer behaviour and stable profit margins. While airports and the Praline category drive a significant share of revenue, performance declines in key regions like Germany and Canada raise concerns. High reliance on discounts is impacting profitability, despite most profits coming from non-discounted products. Overall, the business shows stability but lacks growth momentum, highlighting the need for strategic expansion, pricing optimization, and demand stimulation initiatives.

## **🧭 Executive Overview**
“Stable Performance with Limited Growth Momentum”
-	Revenue shows minimal growth (+0.12%), indicating a stable but stagnant business. 
-	Consistent 40% profit margin generating ~5M profit annually. 
-	Monthly revenue remains flat (31K–38K) → no strong upward trend. 
-	Canada leads with over 2.5M in sales, despite a slight decline of 0.16%, while Germany records the lowest revenue at 1.5M, with a larger decline of 0.34% in 2024. 
-	Airports are the primary revenue contributors, generating 3.76M, which accounts for around 30% of total sales. 
-	The best-selling category is Praline, with Ferrero as the leading brand. Chocolates with 50% cocoa content are the most popular. 
## **👥 Customer Behaviour**
“Consistent Customer Behaviour with No Growth in Engagement”
-	No change in behaviour → 10 orders/customer consistently. 
-	CLV stable at ~184K. 
-	Age group 25–64 contributes ~9.5M annually. 
## **💸 Profitability & Discounts**
“Discount Strategy Eroding Profit Margins”
-	0.75M revenue lost due to discounts. 
-	66% profit from non-discounted products. 
-	Low-volume customers → higher margins (48%). 
-	High-revenue customers → lower margins (40%). 
## **⚖️ Product Demand Trends & Time-based Trends**
“Mid-Size Packs Drive Maximum Demand”
-	50g & 100g packs are most popular. 
-	Dark (50%), Truffle (80%), Praline (50%), and Milk (70%) chocolates, collectively generating over 260K in profit, with a slight dip observed in February. 
-	Sales tend to decline on Mondays and Saturdays. Monthly order trends in 2023–24 show a fluctuating pattern, peaking in January (~43K) and reaching a low in February (~38K).
## **⚠️ Risk Zones**
-	Stagnant Revenue Growth of only 0.12% indicates near saturation or lack of expansion. 
-	Declining performance in key markets like Germany and even slight drops in Canada. 
-	Overdependence on Airports - 30% revenue from one channel → high business risk if demand drops. 
-	Low Margin from High-Value Customers → inefficient pricing or discounting strategy Limited 
-	No growth in orders per customer or CLV → weak retention/upselling strategies. 
-	Mondays and Saturdays underperform → operational inefficiency or low engagement. 

## **💡 Recommendations**
-	Expand into untapped regions or channels beyond airports. 
-	Run targeted campaigns in Germany (discount optimization, localized marketing). 
-	Strengthen retention in Canada to stop further decline. 
-	Implement targeted discounts instead of blanket offers. 
-	Use A/B testing to measure discount effectiveness. 
-	Promote non-discounted high-margin products. 
-	Re-evaluate pricing for high-value customers. 
-	Introduce bundling strategies to increase margin. 
-	Launch loyalty programs to increase orders per customer. 
-	Use personalized recommendations for upselling. 
-	Analyse operational gaps (store timing, staffing, campaigns). 
## **📚 Key Learnings**
- Hands-on experience with Power BI dashboard development  
- Improved skills in DAX and data modeling  
- Strengthened ability to derive business insights from data  
- Learned how to present data in a meaningful and actionable way  

