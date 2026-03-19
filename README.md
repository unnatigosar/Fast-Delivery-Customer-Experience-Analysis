# Fast Delivery Customer Experience Analysis

## Project Overview
This project analyzes customer reviews from quick-commerce delivery platforms to understand the key factors that influence customer satisfaction.

The analysis focuses on four major platforms:
- Zepto  
- Blinkit  
- Swiggy Instamart  
- JioMart  

Using **Power BI**, I built interactive dashboards to evaluate delivery performance, operational reliability, and customer experience.

This project was developed as my **first independent data analytics project** to practice data cleaning, data modeling, and dashboard creation.

---

## Business Problem
Quick-commerce companies compete heavily on **fast delivery and service quality**. However, customer satisfaction depends on several operational factors such as:

- Delivery Time  
- Order Accuracy  
- Product Availability  
- Discounts  
- Service Reliability  

The goal of this analysis is to identify **which operational factors most strongly influence customer ratings**.

---

## Dataset
**Source:** Kaggle  

The dataset contains **5000 customer review records** related to fast delivery services.

### Key Attributes
- Platform  
- Customer Rating  
- Delivery Time  
- Order Accuracy  
- Product Availability  
- Discount Applied  
- Customer Feedback  
- Location  

---

## Tools Used
- **Power BI** – Dashboard development and visualization  
- **Microsoft Excel** – Data cleaning and preparation  
- **DAX** – Creating calculated measures and KPIs  

---

## Data Analysis Workflow
Dataset Collection (Kaggle)  
↓  
Data Cleaning in Excel  
↓  
Data Import into Power BI  
↓  
Data Modeling and DAX Measures  
↓  
Dashboard Development  
↓  
Insight Generation  

---

## Dashboard Preview

### Delivery Experience Performance Dashboard
![Dashboard 1](screenshot/Screenshot_1.png)

This dashboard focuses on delivery performance and operational reliability.

**Key metrics include:**
- Average Customer Rating  
- Order Accuracy Rate  
- Inventory Issue Rate  
- Platform Performance Comparison  
- Delivery Time vs Customer Rating  

---

### Customer Experience Performance Dashboard
![Dashboard 2](screenshot/acreenshot_1.png)

This dashboard focuses on identifying drivers of customer satisfaction.

**Key features include:**
- Experience Index  
- Driver Prioritization Matrix  
- Customer Experience Leakage  
- Impact Simulation of Improving Order Accuracy  
- Experience Index by Platform  

---

## Key Insights

### Inventory availability affects customer satisfaction
Orders affected by stock availability issues tend to receive lower customer ratings.

### Order accuracy influences customer experience
Incorrect orders contribute to negative feedback and reduced ratings.

### Delivery speed has moderate impact
Delivery time appears less influential compared to operational reliability.

### Discounts have limited influence on ratings
Discount availability does not significantly change average customer ratings.

---

## Project Structure
fast-delivery-customer-experience-analysis

README.md

data/
  fast_delivery_reviews.xlsx

dashboard/
  quick_commerce_dashboard.pbix

screenshots/
  dashboard1.png
  dashboard2.png

---

## Limitations
The dataset shows relatively balanced distributions across several operational variables, which may indicate a simulated or evenly distributed dataset.

Therefore, the insights should be interpreted as **analytical patterns rather than exact real-world benchmarks**.

---

## What I Learned
Through this project I gained hands-on experience with:

- Data cleaning and preparation  
- Building Power BI dashboards  
- Creating DAX measures and KPIs  
- Analyzing customer feedback data  
- Translating data insights into business recommendations  

---

## Future Improvements
Possible enhancements to this project include:

- Using real operational datasets  
- Performing SQL-based exploratory analysis  
- Building predictive models for customer satisfaction  
- Expanding analysis to additional delivery platforms  
