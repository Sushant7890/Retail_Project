
# Swiggy Analysis Report
## Project Objective
To design and implement an end-to-end Swiggy Data Analytics solution using Microsoft Fabric, SQL, and Power BI that ingests raw operational data into a Lakehouse, performs data cleansing and validation, transforms and models the data using a Star Schema in Fabric Data Warehouse, and delivers an interactive Power BI Semantic Model and dashboard to analyze sales performance, customer behavior, restaurant performance, and delivery efficiency.
## Dataset Used:
- <a href="https://github.com/Sushant7890/Retail_Project/blob/main/fact_orders.csv">Swiggy Sataset</a>

## Questions (KPIs)  
-What is the total number of orders?                                                                                         
-What is the total revenue generated?                                                                
-What is the Average Order Value (AOV)?                                                            
-What is the average delivery time?                                                  
-Which restaurants generate the highest revenue?                                            
-Which cities have the highest number of orders?                                        
-Which restaurants receive the most orders?                                             
-What is the order cancellation rate?                                                      
-What percentage of orders are delivered on time?                                       
-Which delivery partners handle the most orders?                                                
-What is the average delivery time by city?                                                         
-What is the revenue trend by day/month/year?                                                                 
-Which dishes are ordered most frequently?                                                    
-Which payment methods are most commonly used?                                                 
-What is the average number of orders per customer?                                                         
-Which customer segments generate the highest revenue?                                                                              
-What is the month-over-month revenue growth?                                                                                        
-What is the month-over-month order growth?                                              
-Which locations have the highest delivery delays?                                                                         
-What are the top 10 restaurants based on revenue and order volume?     

## Dashboard Interaction
- <a href="https://github.com/Sushant7890/Retail_Project/blob/main/Swiggy_PBI_Report.pbix">View Dashboard</a>

## Process 
The dashboard follows a clear and logical analysis flow. It begins with overall business KPIs, followed by order, revenue, restaurant, customer, and delivery performance analysis. This approach provides a comprehensive view of Swiggy's business performance and helps identify trends, operational issues, and opportunities for improvement.

-Start with key business metrics including total orders, total revenue, average order value, average delivery time, and total customers.                                                      
-Analyze order and revenue trends across different dates, cities, restaurants, and locations.                                                                                        
-Evaluate restaurant and dish performance to identify top-performing restaurants and frequently ordered dishes.                                                            
-Assess customer behavior including order frequency, customer distribution, and revenue contribution.                                                                 
-Analyze delivery performance including average delivery time, on-time delivery rate, and delivery delays.                                                                              
-Identify cancellation patterns and operational issues that may impact customer satisfaction.                                                                        
-Compare city and location-wise performance to identify high-performing and underperforming areas.                                                                            
-Identify key patterns and trends that can help improve revenue, customer experience, restaurant performance, and delivery efficiency.                                                           

## Dashboard
![HR Dashboard](https://github.com/Sushant7890/Retail_Project/blob/main/e505d07a-6683-4f22-ab6e-bef8c0727a1b.png)

## Project Insight:   
Revenue Baseline: The platform generated ₹53.01M in Total Sales across 197.43K orders.                                          

Average Order Value (AOV): The portfolio shows a steady AOV of ₹268.51, reflecting strong basket size per transaction.                                                                                    

High Customer Satisfaction: Maintained a 4.34 out of 5 rating scale across a large dataset of 5.59M reviews.                                                                               

Dominant Food Category: Non-Veg items generate 64.08% (₹33.97M) of overall revenue, outperforming Veg items (35.92% / ₹19.04M) by nearly 1.8x.                                                              

Top Performing Restaurant: KFC is the highest revenue-generating chain brand, contributing ₹4.2M in total sales.                                                                              

Top Fast-Food Chains: Fast food chains (KFC, McDonald's, Pizza Hut, Burger King, Domino's) account for a significant share of top brand revenue, led by KFC (₹4.2M) and McDonald's (₹3.3M).                                   

Top State Market: Karnataka leads all states by a wide margin, contributing ₹5.5M in total revenue.                                                                                                            

Geographical Concentration: The top 3 states—Karnataka (₹5.5M), Uttar Pradesh (₹3.1M), and Telangana (₹3.0M)—drive the majority of sales volume.                                                                                                      

Consistent Daily Demand: Daily revenue remains surprisingly uniform throughout the week, fluctuating minimally between ₹7.4M (Mon–Tue) and ₹7.8M (Saturday).                                                                                            

Peak Ordering Day: Saturday brings in the highest daily revenue at ₹7.8M, demonstrating a slight weekend uplift.                                                                                                                                       

Monthly Recovery Trend: Revenue hit a low point in February (₹6.27M) before rebounding to peak levels in May and August (₹6.79M).  

## Strategic Action Items & Portfolio Takeaways

Expansion Potential: Focus targeted expansion marketing on underperforming high-population states like Maharashtra (₹3.0M) and Delhi (₹2.8M) to capture market share closer to Karnataka's levels.                                                                     

Menu Optimization: Create targeted Non-Veg meal bundles and family offers to capitalize on high consumer demand.                                                                                             

AOV Growth Strategy: Implement cross-selling and dessert/beverage add-on prompts at checkout to push the current ₹268.51 AOV toward ₹300+.                                                                        

Mid-Week Engagement: Leverage Veg-focused deals or localized discounts on Mondays and Tuesdays to boost lower-performing daily revenue slots.                                           

## Conclusion:
This Swiggy analytics project demonstrates strong performance across core operational metrics, highlighted by ₹53.01M in sales, high customer satisfaction (4.34 rating), and stable daily ordering patterns. The analysis clearly establishes Non-Veg food categories (64% share), fast-food chains led by KFC, and Karnataka as the primary drivers of platform revenue.

Moving forward, revenue growth can be accelerated by focusing on three strategic pillars: expanding presence in underperforming metro states like Maharashtra and Delhi, creating cross-selling bundles to push AOV past ₹300, and launching targeted weekday deals to optimize order volumes during mid-week periods.
