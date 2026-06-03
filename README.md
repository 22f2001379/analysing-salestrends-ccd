# Optimising Café Coffee Day (IIT Madras) Sales Through Data Analytics

A comprehensive business analytics and inventory optimisation project conducted at the Café Coffee Day (CCD) outlet inside the Indian Institute of Technology Madras (IITM).

This project analyses approximately 90 days of real-world sales data collected directly from the outlet to uncover customer purchasing behaviour, identify revenue drivers, forecast demand, and recommend inventory optimisation strategies.

Unlike many academic projects that rely on publicly available datasets, this project involved primary data collection, direct interaction with store management, manual data digitisation, statistical analysis, forecasting, and business recommendation development.

---

## Project Highlights

✅ Primary data collected from a real business environment

✅ 90 days of sales observations

✅ Approximately 800 transaction records analysed

✅ Statistical and business analytics techniques applied

✅ Demand forecasting and inventory optimisation

✅ Actionable recommendations for business operations

✅ Complete project lifecycle documented

* Project Proposal
* Mid-Term Submission
* Final Report
* Presentation Deck
* Analysis Notebook
* Mathematical Foundations Document

---

## Business Context

The CCD outlet at IIT Madras operates under a unique environment.

Unlike conventional CCD outlets, pricing is regulated by the Committee for Monitoring General Facilities for Students (CMGFS), resulting in heavily subsidised pricing for students. This creates operational challenges related to profitability, inventory planning, and resource allocation.

The primary goal of this project was to identify opportunities to improve operational efficiency and inventory management through data-driven decision-making.

---

## Objectives

The project aimed to answer the following business questions:

* Which products contribute the most revenue?
* What sales patterns exist across time?
* Are snack and beverage purchases related?
* Which products require inventory scaling?
* How can CCD improve revenue and operational efficiency?
* Can future demand be forecasted accurately?

---

## Dataset Overview

### Data Collection

Sales data was collected directly from the CCD IITM outlet by photographing daily billing summaries and manually transcribing them into a structured digital dataset.

### Dataset Characteristics

| Attribute          | Value                  |
| ------------------ | ---------------------- |
| Observation Period | Aug 2024 – Dec 2024    |
| Duration           | ~90 Days               |
| Records            | ~800                   |
| Source             | CCD Billing Summaries  |
| Collection Method  | Manual Digitisation    |
| Domain             | Food & Beverage Retail |

### Features

| Column        | Description        |
| ------------- | ------------------ |
| Date          | Transaction Date   |
| Category      | Food / Beverage    |
| Sub-category  | Product Group      |
| Item Name     | Individual Product |
| Quantity Sold | Units Sold         |
| Net Sales (₹) | Revenue Generated  |

---

## Methodology

### 1. Descriptive Statistics

Used to understand:

* Sales distribution
* Average performance
* Revenue variability
* Product-level trends

### 2. Pareto Analysis (80/20 Rule)

Used to identify the small subset of products responsible for the majority of revenue.

Business Benefits:

* Inventory prioritisation
* Menu optimisation
* Product visibility improvements

### 3. Time Series Analysis

Used to study:

* Daily demand patterns
* Weekend effects
* Peak sales periods

Business Benefits:

* Staffing optimisation
* Inventory planning
* Demand monitoring

### 4. Pearson Correlation Analysis

Used to measure relationships between snack and beverage sales.

Business Benefits:

* Cross-selling opportunities
* Combo offer design

### 5. Forecasting

Demand forecasting was performed using:

* Holt-Winters Exponential Smoothing
* Simple Moving Average (SMA)

Evaluation Metrics:

* MAE
* MAPE
* R² Score

Business Benefits:

* Stockout prevention
* Forecast-driven inventory management

---

## Mathematical Foundations

The repository includes a supplementary document explaining the statistical and forecasting formulae used throughout the analysis.

Covered concepts include:

### Descriptive Statistics

* Mean
* Median
* Standard Deviation
* Coefficient of Variation (CV)

### Relationship Analysis

* Pearson Correlation Coefficient

### Forecast Evaluation

* Mean Absolute Error (MAE)
* Mean Absolute Percentage Error (MAPE)
* Coefficient of Determination (R²)

These measures were used to evaluate sales behaviour, demand variability, forecasting performance, and customer purchasing patterns.

---

## Key Findings

### Revenue Concentration

A small percentage of products generated the majority of outlet revenue.

Top-performing products included:

* Tandoori Chicken Sandwich
* Gourmet Belgian
* Spinach & Corn Sandwich
* Butter Scotch
* Café Frappe
* Cappuccino
* Devil's Own
* Smoked Chicken

Result:

* Approximately 20% of products generated over 80% of revenue.

---

### Weekend Sales Peaks

Strong temporal patterns emerged.

Observed customer traffic:

* Weekdays: 200–300 customers
* Weekends: More than 350 customers

Implications:

* Increased staffing requirements
* Additional inventory allocation
* Improved operational planning

---

### Food vs Beverage Revenue

One of the most interesting findings challenged conventional assumptions.

Revenue Contribution:

| Category  | Contribution |
| --------- | ------------ |
| Beverages | 53.3%        |
| Food      | 46.7%        |

Although CCD is traditionally viewed as a coffee-focused business, food contributes nearly half of total revenue at the IITM outlet.

---

### Cross-Selling Opportunities

Pearson Correlation:

r = 0.10

Interpretation:

* Weak positive relationship
* Limited natural bundling behaviour
* Opportunity for targeted combo offers

Potential Examples:

* Iced Mocha + Tandoori Chicken Sandwich
* Cappuccino + Brownie
* Cold Coffee + Garlic Bread

---

### Inventory Forecasting

Products requiring substantial inventory expansion included:

| Product          | Additional Units Required |
| ---------------- | ------------------------- |
| TA Iced Mocha    | ~2362                     |
| Cheese           | ~1014                     |
| Tandoori Chicken | ~750                      |
| Classic Garlic   | ~604                      |
| Chilli Cheese    | ~456                      |

Forecasting models demonstrated low forecasting error and high reliability.

---

## Strategic Recommendations

### Inventory Management

* Prioritise high-revenue SKUs
* Scale inventory using forecasts
* Reduce low-performing inventory

### Revenue Growth

* Promote top-selling products
* Improve visibility of food offerings
* Introduce targeted combo offers

### Operations

* Increase staffing during weekends
* Allocate inventory based on peak-hour demand
* Prepare for campus events and festivals

### Customer Experience

* Improve product display visibility
* Encourage upselling opportunities
* Enhance product availability during peak periods

---

## Technology Stack

### Programming

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib

### Tools

* Jupyter Notebook
* Google Sheets
* Microsoft PowerPoint

---

## Repository Structure

```text
├── CCD_Data_Analysis_BDM.ipynb
├── 22f2001379_BDM_Primary_Proposal.pdf
├── 22f2001379_Mid_Term_Report.pdf
├── 22f2001379_BDM_FinalReport.pdf
├── Optimising CCD IITM Sales Through Data Analysis.pptx
├── Math_Formulae_used_in_BDM_report.pdf
└── README.md
```

---

## Repository Contents

### Project Proposal

Defines the business problem, project objectives, planned methodology, expected outcomes, and implementation roadmap.

### Mid-Term Submission

Presents initial findings, descriptive analytics, Pareto analysis, and preliminary recommendations.

### Final Report

Comprehensive business analysis including forecasting, inventory optimisation, and strategic recommendations.

### Presentation

Executive-level summary of methodology, insights, and recommendations.

### Jupyter Notebook

Contains the complete analytical workflow and code implementation.

### Mathematical Formulae Document

Provides the statistical and forecasting equations used throughout the project.

---

## Results

This project demonstrates how business analytics can be applied in a real retail environment to support operational decision-making.

Key outcomes include:

* Inventory optimisation recommendations
* Revenue growth opportunities
* Forecast-driven stocking strategies
* Customer demand insights
* Product prioritisation framework
* Actionable business recommendations

---

## Future Work

Potential extensions include:

* Interactive Power BI Dashboard
* Automated Inventory Management System
* Machine Learning-Based Demand Forecasting
* Customer Segmentation Analysis
* Recommendation Systems for Combo Offers
* Real-Time Sales Monitoring Dashboard

---

## Author

Renee Keerthana Paturi

BS Degree Programme in Data Science and Applications

Indian Institute of Technology Madras

---

## Acknowledgements

Special thanks to the management and staff of the Café Coffee Day IIT Madras outlet for permitting data collection and providing operational insights that made this project possible.

---

## Disclaimer

This project was conducted for academic and analytical purposes. Findings and recommendations are specific to the CCD IIT Madras outlet and the analysed dataset. They should not be interpreted as official recommendations from IIT Madras or Café Coffee Day.
