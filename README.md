# Quantium Data Analytics Virtual Experience Program

## Project Overview

This project was completed as part of the Quantium Data Analytics Virtual Experience Program on Forage. The simulation provided hands-on experience in data analytics, customer segmentation, exploratory data analysis (EDA), commercial insights generation, and strategic recommendations for a retail client.

The objective was to analyze transaction and customer data to uncover purchasing behaviors, identify valuable customer segments, and provide data-driven business recommendations.

## Business Problem

Quantium’s retail client wanted to better understand:

* Customer purchasing behavior
* Key customer segments driving sales
* Product preferences across customer groups
* Opportunities to improve marketing effectiveness and revenue growth

Using transaction and customer datasets, the analysis focused on generating actionable insights for business stakeholders.

## Project Tasks

### Task 1: Data Preparation and Customer Analytics

Files: 
* Quantium_DA_Task_1.ipynb
* QVI_purchase_behaviour.csv
* QVI_transaction_data.xlsx

- Data cleaning: changed the date from integer format to datetime data type, removed salsas and outliers 
- Analysed purchase behaviours of different customers (total sales, grouped by:
  - LIFESTAGE: customer attribute that identifies whether a customer has a family or not and what point in life they are at
  - MEMBER_TYPE: customer segmentation used to differentiate shoppers by the price point of products they buy and the types of products they buy. It is used to identify whether customers may spend more for quality or brand or whether they will purchase the cheapest options.
- A deeper dive into the Mainstream Young Singles/Couples segment to determine their preferences (chip brand and packet size) over other segments

**Insights:**
- The three highest contributing segments to total sales are: 1. Budget older families, 2. Mainstream young singles/couples, 3. Mainstream retirees
- Older families have largest avg no of packets purchased per customer, while the mainstream young singles/couples have the largest population
- Across most segments, Kettles chips and 175g packets are the most purchased
- Minstream young singles/couple are 28% more likely to purchase Tyrells chips than other segments, and 32% more likely to purchase 270g chip packets which are Twisties chips

### Visulaizations
![alt text](https://github.com/asna-amjad/Quantium-Data-Analytics-Job-Simulation/blob/08cd1ed00ddebf78e86f383e56a8c09effd3d02d/QVI_Images/total_sales_1.png)
![alt text](https://github.com/asna-amjad/Quantium-Data-Analytics-Job-Simulation/blob/08cd1ed00ddebf78e86f383e56a8c09effd3d02d/QVI_Images/cutomer_lifestage_2.png)

### Task 2: Experimentation and Uplift Testing

Files: 
* Quantium_DA_Task_2.ipynb
* QVI_data.csv
  
- Three stores (77, 86, 88) undergo a new store layout with the trial period in Feb-Apr 2019
- Used the total sales and number of customers metric to generate a combined score to compare the trial and potential control stores with using Pearson correlations and magnitude distances
- Determined if difference in performance of those metrics of the control stores (stores with the highest score) compared to the trial store is significant using hypothesis test

**Insights:**
- Control and trial store pairs are:
  - 77 and 233
  - 86 and 155
  - 88 and 237
- For the total sales, store 77 saw a statistically significant increase (above the 95% control threshold) in Mar and Apr while store 86 saw an increase in Mar
- For the number of customers, both stores 77 and 86 saw significant increases in at least 2 months
- No significant change in performance due to the trial in store 88

### Visulaizations
![alt text](https://github.com/asna-amjad/Quantium-Data-Analytics-Job-Simulation/blob/08cd1ed00ddebf78e86f383e56a8c09effd3d02d/QVI_Images/TrialvsControl_3.png)
![alt text](https://github.com/asna-amjad/Quantium-Data-Analytics-Job-Simulation/blob/08cd1ed00ddebf78e86f383e56a8c09effd3d02d/QVI_Images/TrialvsControl_4.png)
![alt text](https://github.com/asna-amjad/Quantium-Data-Analytics-Job-Simulation/blob/08cd1ed00ddebf78e86f383e56a8c09effd3d02d/QVI_Images/TrialvsControl_5.png)
![alt text](https://github.com/asna-amjad/Quantium-Data-Analytics-Job-Simulation/blob/08cd1ed00ddebf78e86f383e56a8c09effd3d02d/QVI_Images/performance_6.png)
![alt text](https://github.com/asna-amjad/Quantium-Data-Analytics-Job-Simulation/blob/08cd1ed00ddebf78e86f383e56a8c09effd3d02d/QVI_Images/performance_7.png)
![alt text](https://github.com/asna-amjad/Quantium-Data-Analytics-Job-Simulation/blob/08cd1ed00ddebf78e86f383e56a8c09effd3d02d/QVI_Images/performance_8.png)

### Task 3: Analytics and commercial application
- Prepared a report in Powerpoint highlighting key insights from Tasks 1 and 2 using the Pyramid Principle

**Tools & Technologies**

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

### Key Insights

High-Value Customer Segment

The most profitable customer segment consisted of:

* Mainstream Young Singles/Couples
* Frequent purchasers
* Higher overall spending behavior

Product Preferences

* Certain chip brands generated significantly higher sales.
* Larger pack sizes contributed more revenue per transaction.
* Customer segments displayed distinct purchasing preferences.

Revenue Drivers

Revenue growth was primarily driven by:

* Purchase frequency
* Average transaction value
* Brand loyalty

### Business Recommendations

1. Develop targeted marketing campaigns for high-value customer segments.
2. Increase promotions for top-performing products.
3. Introduce loyalty programs to encourage repeat purchases.
4. Personalize offers based on purchasing behavior and customer demographics.
5. Optimize inventory planning around customer demand patterns.

### Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis
* Customer Segmentation
* Business Intelligence
* Data Visualization
* Commercial Analytics
* Stakeholder Reporting
* Insight Generation
* Strategic Recommendations

### Learning Outcomes

Through this project, I gained experience in:

* Translating business problems into analytical solutions
* Working with real-world retail transaction data
* Extracting actionable business insights
* Presenting findings to stakeholders
* Applying data analytics techniques to support business decisions

### Certificate

Completed the Quantium Data Analytics Virtual Experience Program offered through Forage.
