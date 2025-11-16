# Amazon Sales & Reviews Analysis in Power BI

This project uses **Power BI Desktop** and **Excel** to conduct a comprehensive analysis of Amazon product **sales performance**, **customer reviews**, and **product trends**.  
The goal is to monitor key KPIs like **YTD Sales**, **QTD Sales**, **Products Sold**, and **Reviews**, and to generate actionable insights.

---

## Dashboard Demo

![Dashboard Demo](./images/Dashboard_Demo.gif)

---

## Key Features

📌 **Data Visualization**: Interactive dashboards with rich visuals for key metrics.

📌 **Time-Based Analysis**: YTD and QTD performance across months and weeks.

📌 **Product & Category Insights**: Identify top-performing products and categories.

📌 **Review & Feedback Tracking**: Analyse customer engagement through review counts.

---

![Dashboard Overview](https://github.com/PrajwalGpy/Project-PowerBI-AmazonSales-ReviewsAnalysis/blob/main/images/Screenshot%202025-11-16%20115443.png)

---

## Tools Used

**Power BI**: For data modeling, visualization, DAX measures, and dashboard creation.

**Excel/CSV**: For raw data storage, cleaning, and preprocessing.

**Power Query**: For data transformation and shaping.

**DAX**: For KPI and time-intelligence calculations.

---

## Steps in Project

✔️ Requirement Gathering / Business Understanding  
✔️ Data Walkthrough  
✔️ Data Connection (Excel to Power BI)  
✔️ Data Cleaning / Quality Check  
✔️ Data Modeling (Relationships, Star Schema)  
✔️ Data Processing & Transformations  
✔️ DAX Calculations for KPIs  
✔️ Dashboard Layout Planning  
✔️ Charts Development and Formatting  
✔️ Dashboard / Report Development  
✔️ Insights Generation and Storytelling

---

## Business Requirement

To conduct a **comprehensive analysis of Amazon product sales and customer reviews** in order to:

- Track **YTD and QTD sales performance**
- Understand **product movement** and **top-performing SKUs**
- Monitor **customer engagement** using review counts
- Identify trends and opportunities for optimization using interactive visualizations in **Power BI**

---

## KPI’s Requirements

**1. YTD Sales:**  
Monitor the total revenue generated from the beginning of the year to date.

**2. QTD Sales:**  
Track quarterly revenue to identify performance trends and fluctuations within the current quarter.

**3. YTD Products Sold:**  
Analyse the total number of products sold year-to-date to understand product movement and demand.

**4. YTD Reviews:**  
Keep track of the number of product reviews received year-to-date to assess customer engagement and feedback.

![KPIs Screenshot](https://github.com/PrajwalGpy/Project-PowerBI-AmazonSales-ReviewsAnalysis/blob/main/images/Screenshot%202025-11-16%20115235.png)

---

## Chart’s Requirements

<ol>

<h3><li> YTD Sales by Month (Line Chart):</li></h3>  
<ul>  
  <li><b><ins>Objective:</ins></b> Visualize month-wise YTD sales trends to identify seasonal patterns and growth over time.</li>  
  <li><b>Insight:</b> Helps understand which months contribute the most to yearly revenue.</li>  
  <li><b>Chart Type:</b> Line Chart.</li>  
  <br>
  <div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
      <img src="https://github.com/PrajwalGpy/Project-PowerBI-AmazonSales-ReviewsAnalysis/blob/main/images/Screenshot%202025-11-16%20115254.png" alt="YTD Sales by Month" width="250" height="200" />
  </div>
</ul>

<h3><li> YTD Sales by Week (Column Chart):</li></h3>  
<ul>  
  <li><b><ins>Objective:</ins></b> Display weekly sales performance to capture short-term fluctuations and campaign impact.</li>  
  <li><b>Insight:</b> Useful for analyzing promotions, flash sales, and weekly trends.</li>  
  <li><b>Chart Type:</b> Column Chart.</li>  
  <br>
  <div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
      <img src="https://github.com/PrajwalGpy/Project-PowerBI-AmazonSales-ReviewsAnalysis/blob/main/images/Screenshot%202025-11-16%20115346.png" alt="YTD Sales by Week" width="250" height="200" />
  </div>
</ul>

<h3><li> Sales by Product Category (Text / Heat Map):</li></h3>  
<ul>  
  <li><b><ins>Objective:</ins></b> Provide a high-level view of sales distribution across different product categories.</li>  
  <li><b>Insight:</b> Highlights which categories drive most revenue and which need attention.</li>  
  <li><b>Chart Type:</b> Text Table / Heat Map.</li>  
  <br>
  <div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
      <img src="https://github.com/PrajwalGpy/Project-PowerBI-AmazonSales-ReviewsAnalysis/blob/main/images/Screenshot%202025-11-16%20115400.png" width="250" height="200" />
  </div>
</ul>

<h3><li> Top 5 Products by YTD Sales (Bar Chart):</li></h3>  
<ul>  
  <li><b><ins>Objective:</ins></b> Highlight the top 5 products based on YTD sales revenue.</li>  
  <li><b>Insight:</b> Helps identify key revenue-generating products to prioritize inventory and marketing.</li>  
  <li><b>Chart Type:</b> Bar Chart.</li>  
  <br>
  <div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
      <img src="https://github.com/PrajwalGpy/Project-PowerBI-AmazonSales-ReviewsAnalysis/blob/main/images/Screenshot%202025-11-16%20115414.png" alt="Top 5 Products by YTD Sales" width="250" height="200" />
      
  </div>
</ul>

<h3><li> Top 5 Products by YTD Reviews (Bar Chart):</li></h3>  
<ul>  
  <li><b><ins>Objective:</ins></b> Identify the top 5 products with the highest YTD reviews.</li>  
  <li><b>Insight:</b> Shows which products receive the most customer interaction and feedback.</li>  
  <li><b>Chart Type:</b> Bar Chart.</li>  
  <br>
  <div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
      <img src="https://github.com/PrajwalGpy/Project-PowerBI-AmazonSales-ReviewsAnalysis/blob/main/images/Screenshot%202025-11-16%20115428.png" width="250" height="200" />
      
  </div>
</ul>

</ol>

---

## Dashboard Insights

### Highlights:

1. **Seasonality in Sales**: Strong Q2 spike driven by Prime Day and festive period
2. **Best Sellers**: Electronics & Home Appliances dominate revenue
3. **Customer Feedback**: Higher ratings correlate with faster-moving products
4. **Growth Opportunities**: Certain categories under review low-performing products

### Key Insights:

1. **Sales Trends:**  
   Clear patterns in monthly and weekly YTD sales help understand seasonality and campaign impact.

2. **Category Performance:**  
   Certain product categories contribute significantly more to revenue, guiding strategic focus.

3. **Product Performance:**  
   Top 5 products by sales and reviews reveal the most impactful items in terms of revenue and customer engagement.

4. **Customer Engagement:**  
   YTD reviews help understand how actively customers interact with products and where satisfaction or dissatisfaction is concentrated.

### Interactive Features:

- Drill-through options for detailed product-level and category-level insights.
- Custom slicers for time period, category, and product segmentation.
- KPI cards and matrix visuals to monitor performance in real-time.

---

## 📂 How to Use

1. Download the Power BI file: **`Project(PowerBI)AmazonSales&ReviewsAnalysis.pbix`**
2. Open the file in **Power BI Desktop**.
3. Make sure the data source (`Amazon_Combined_Data.xlsx`) is placed in the correct relative path if needed.
4. Explore dashboards using slicers, filters, and drill-through actions.

---

## File Details

- **File Name**: `Project(PowerBI)AmazonSales&ReviewsAnalysis.pbix`  
  **Description**: Final Power BI report file.

- **File Name**: `Amazon_Combined_Data.xlsx`  
  **Description**: Combined dataset containing Amazon sales and review data.

(Upload both files to this repository so others can open and explore the report.)

---

## 📧 Contact

For any queries or feedback, feel free to reach out:

**Prajwal Gopal Poojary**  
📧 Email: `prajwalgpa@gmail.com`  
🔗 Portfolio: <https://prajwalgopalpoojary.netlify.app>  
💼 LinkedIn: <https://linkedin.com/in/prajwalgopalpoojary/>

---

## Acknowledgments

Special thanks to the **online data community** and resources that inspired the dataset and analysis approach.  
A big shoutout to [Data Tutorials](https://www.youtube.com/@datatutorials1) for their helpful Power BI tutorials that guided the project-building approach.

---

## 🔗 Links

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://prajwalgopalpoojary.netlify.app/)  
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prajwalgopalpoojary/)  
[![x](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/prajwalgpa)

---
