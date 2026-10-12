# First Data Analyst Project Portofolio
## About Me
Hi, I'm Pujawati, an aspiring Data Analyst. skilled in Excel, Python, SQL, and Tableau. I'm passionate about transforming complex data into clear, actionable insights that optimize operations and drive business decisions.

## Brazilian E-Commerce (Olist) Tableau Report
This was my first interactive dashboard project using Tableau. It represents a key step in my journey to analyze and visualize complex datasets. I’m passionate about using Tableau to uncover hidden trends, tell compelling data stories, and drive meaningful business decisions.

### Data Source and Resources
Data Source: [Olist Data Source](https://www.kaggle.com/datasets/sakshisatre/tips-dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce))  
Tools Used: Python, Tableau  
Dashboard: [View Tableau Dashboard](https://public.tableau.com/views/OlistDashboard_17910372146380/OlistDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### About Dataset
This project analyzes the **Olist Brazilian E-Commerce Dataset**, the largest department store marketplace in Brazil. The dataset spans over 97000+ orders between 2017 and 2018. It contains detailed information on order statuses, customer demographics, payment methods, product categories, seller locations, and actual vs. estimated delivery timelines. 
### Problem Statement
In the competitive e-commerce sector, marketplace operators need data-driven insights to make strategic decisions around supply chain logistics, merchant onboarding, marketing campaigns, and regional expansion.
As a Data Analyst, my primary objective was to clean, transform, and visualize Olist’s relational dataset to reveal actionable business insights across sales performance, order delivery times, and geographic performance.
### Analytics Question
1. How have total sales revenue and order volume developed over time across different months and years?
2. What is the most and least efficient shipment state?
3. Which state has the highest late shipment rate?
4. How does shipping freight cost correlate with order delivery delays?
      
### Analysis Results

<img width="1599" height="1583" alt="Olist Dashboard - Copy - Copy" src="https://github.com/user-attachments/assets/95499837-299d-49cd-bcfd-5a470034965f" />

1. Sales & Order Trends: Total sales revenue and order volume demonstrate a strong upward trend year-over-year from 2017 to 2018.R$135k in January 2017 to R$1.08M in January 2018. Sales revenue has increased 700%.


<img width="1599" height="1002" alt="11" src="https://github.com/user-attachments/assets/a3fcc1b2-993e-43a1-99aa-fc0145d47fe8" />

2. Most Efficient: Delivery operations are most efficient in the Southern and Southeastern regions of Brazil, ranging between 2.89% and 5.75%.   Least Efficient: Delivery operations are least efficient in the Northeast region of Brazil, late Rate reaching up to 23.21%. Delivery operations are ineffective in the Northeast due to a lack of local sellers, forcing long-distance shipping from southern hubs and driving late rates up to 23.21%, compared to just 2.89%–5.75% in high seller-density areas

<img width="1599" height="838" alt="Olist Dashboard - Copy" src="https://github.com/user-attachments/assets/86a28580-871b-4a93-abf9-3a7413d67b9a" />

3. Highest Volume of Delayed/Impacted Orders: São Paulo (SP) accounts for the highest total number of affected orders (310 orders). Moreover, there is a strong positive correlation between freight costs and delivery delays. As shipping costs increase, average delivery delay days also increase significantly. Impact of High Freight: For high freight values (R$35 - R$45), delays spike dramatically to 15 – 20 days.
This may affect long-term customer satisfaction. This will likely cause churn due to frustration with delivery delays and expensive shipping costs.

### Recommendations for Stakeholders
1. **Address Geographic Mismatch:** Offer commission promotions to onboard new sellers in the Northeast region and rent Distribution Centers (DC) in that area to store inventory from Southern sellers.
2. **Dynamic ETA:** Automatically adjust ETAs based on geographic distance (+3 days for the Northeast region).
3. **Smart Order Routing:** Reroute orders to the nearest seller to the buyer to reduce cancellations.   
