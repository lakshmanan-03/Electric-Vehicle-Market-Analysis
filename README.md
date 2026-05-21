# Electric-Vehicle-Market-Analysis
End-to-end EV market analysis project featuring data cleaning, exploratory analysis, and interactive Power BI dashboards.
# Electric Vehicle Market Analysis

## Project Overview

This project analyzes Electric Vehicle (EV) market data to understand the relationship between pricing, performance, efficiency, customer satisfaction, and smart technology adoption.

The analysis was performed using **Excel, Python, and Power BI** to clean, analyze, and visualize EV market trends.

---

## Project Objectives

The main objectives of this project are:

- Understand factors influencing EV pricing
- Analyze customer preferences
- Study performance vs affordability trade-offs
- Explore smart EV technology impact on pricing
- Build an interactive Power BI dashboard for insights

---

## Tools & Technologies Used

- **Excel** — Data cleaning, feature engineering, and metric creation  
- **Python** — Exploratory Data Analysis (EDA)  
- **Pandas** — Data manipulation and analysis  
- **NumPy** — Numerical operations  
- **Matplotlib** — Data visualization  
- **Jupyter Notebook** — Python analysis environment  
- **Power BI** — Interactive dashboard creation  
- **DAX** — KPI calculations and measures  

---

## Dataset Features

The dataset contains EV-related information such as:

- Brand
- Model
- Year
- Price (USD)
- Battery Capacity
- Driving Range
- Charging Speed
- Horsepower
- Torque
- Top Speed
- Customer Rating
- Autopilot Level
- Warranty Years
- Country
- Annual Sales Units

---

## Custom Metrics Created in Excel

To improve business analysis, the following custom metrics were created:

### 1. Miles_per_kWh
Measures EV energy efficiency.

### 2. Cost_per_Mile
Evaluates affordability relative to driving range.

### 3. Customer_Value_Index
Measures customer satisfaction compared to vehicle price.

### 4. Performance_Score
Evaluates vehicle performance using horsepower, torque, and acceleration.

Additional category columns created:

- EV Price Category
- Charging Category
- Smart EV Classification

---

## Python Analysis

The dataset was analyzed in **Python (Jupyter Notebook)** using exploratory data analysis techniques.

### Analysis Performed

- Data validation
- Missing value check
- Duplicate record check
- Statistical summary using `describe()`
- Correlation analysis
- Data visualization

### Key Python Visualizations

- Price vs Horsepower
- Range vs Customer Rating
- Autopilot Level vs Price
- Performance Score vs Cost per Mile

---

## Power BI Dashboard

An interactive **3-page Power BI dashboard** was created to visualize EV market insights.

### Page 1 — Executive Overview

This page provides a high-level EV market summary including:

- Average EV Price
- Average Driving Range
- Average Customer Rating
- Average Energy Efficiency
- Average Cost per Mile
- EV Price Category Distribution
- Average Price by Autopilot Level
- Country-wise EV Distribution

### Page 2 — Performance & Efficiency Analysis

This page focuses on performance and affordability relationships:

- Performance Score vs Cost per Mile
- Range vs Customer Rating
- Horsepower vs Price
- Top 10 Most Efficient EV Brands

### Page 3 — Customer & Technology Insights

This page explores customer behavior and technology adoption:

- Customer Rating by Autopilot Level
- Charging Speed vs Customer Satisfaction
- Warranty Analysis by EV Category

Interactive slicers were added for:
- Country
- EV Price Category

---

## Dashboard Preview

### Page 1 — Executive Overview

![Dashboard Page 1](screenshots/dashboard_page1.png)

### Page 2 — Performance & Efficiency Analysis

![Dashboard Page 2](screenshots/dashboard_page2.png)

### Page 3 — Customer & Technology Insights

![Dashboard Page 3](screenshots/dashboard_page3.png)

---

## Key Findings

- EVs with higher horsepower are generally more expensive.
- Customers prefer EVs with longer driving range.
- Higher autopilot levels increase EV pricing.
- High-performance EVs often have higher cost per mile.
- Mid-range EVs provide a strong balance between cost, performance, and efficiency.

---

## Project Outcome

This project helped strengthen skills in:

- Data Cleaning
- Exploratory Data Analysis
- Python Programming
- Dashboard Development
- Data Visualization
- Business Storytelling
- Power BI Reporting

---

## Repository Structure


EV-Market-Analysis/
│── data/
│   ├── ev_dataset.xlsx
│
│── notebooks/
│   ├── ev_analysis.ipynb
│
│── dashboard/
│   ├── EV_Analysis_Project.pbix
│
│── screenshots/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│   ├── dashboard_page3.png
│
│── README.md
│── requirements.txt

