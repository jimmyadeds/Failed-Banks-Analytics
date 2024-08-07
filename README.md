# Failed Banks Analytics

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](recommendations)
- [Limitations](limitations)
- [References](references)
  
### Project Overview
---
This project performs exploratory analysis of failed banks in the United States between 2000 and 2024. It analyzes total banks by state, year and month. Based on the analysis, trends are identified, data-driven insights are generated, and recommendations are provided for future improvements.

### Data Sources
---
The dataset used is a CSV file sourced from data.gov. It is titled "FDIC Failed Banks List". It contains data on failed banks in the US reported to Federal Deposit Insurance Corporation (FDIC). [link](https://catalog.data.gov/dataset/fdic-failed-bank-list).

### Tools
---
 - Power BI Desktop is used for this project.
    - Within Power BI Desktop, the following tools are used for different purposes.
      - *Power BI Desktop* for data acquisition through the web and to access Report view, Table view, Model view and Dax Query view,
      - *Power Query Editor* for data preview and cleaning,
      - *Report View* for visualisation and data pane, data modelling such as date table, 
      - *Table View* for data transformation such as creating new table, adding columns and measures. 
      - *Model View* for data modelling such as creating relationships.
      - *DAX Query View* for repository for the data analysis expressions used for data modelling.    

### Exploratory Data Analysis
---
Exploratory Data Analysis (EDA) is employed to answer key research questions as follows:
  - What is the total number of failed banks, and the total number of states that experienced bank failures?
  - Which of the states recorded the highest number of bank failures?
  - Which year recorded the highest number of bank failures?
  - Is bank failure more common in any particular month of the year?
  - Which state did not experience any bank failures?

### Data Analysis
---
#### What is the total number of failed banks, and the total number of states that experienced bank failures?
  - To answer the questions the following were done. 
    - New measures were created for *total Banks* and *total sales*
    - Consequently, visual cards were used to present it on the dashboard.
      
<img width="71" alt="Screenshot 2024-08-07 134934" src="https://github.com/user-attachments/assets/d62c3135-4091-4bf9-958e-85426317508a">
<img width="72" alt="Screenshot 2024-08-07 135017" src="https://github.com/user-attachments/assets/be8fcfcc-3cbd-4fc7-80a2-f1f3fd84202a">

#### Which of the states recorded the highest number of bank failures?
- 

### Findings
---
Summary of results.
  - Total revenue for the period was $80,567.85, and total units of product items sold was 518.
  - General sales/revenue trended positively in the first four months, peaking in January and April at $8,000 and $6,710, respectively, before declining until August.
  - North America generated the highest revenue overall, with a total of $36,844.
  - Electronics contributed the most to revenue ($34,982), while Beauty products ($2,622) and Books ($1,862) were the least. Home Appliances, Sports, and Clothing occupied the middle positions in descending order.
  - Credit cards were used for the majority of sales but not at all in Europe. Debit cards were the least used, only appearing in Asia. PayPal was exclusively used in Europe.
  - The top 5 product items by sales were:
    1. Canon EOS RS Camera ($3,899.99)
    2. LG OLED TV (2,599.98)
    3. MacBook Pro 16-inch ($2,499.99)
    4. Apple MacBook Pro 16-inch ($2,399)
    5. iPhone 14 Pro ($1,999.98)

### Recommendations
---
1. Leverage Seasonal Trends:
    - Focus marketing efforts in January and April when sales peak.
    - Plan promotions and inventory to capitalize on high-demand periods.
2. Target High-Revenue Regions:
    - Invest more in North American markets, which generate the highest revenue.
    - Explore strategies to boost sales in underperforming regions.
3. Promote High-Performing Categories:
    - As the top revenue contributor, increase marketing for Electronics in North America.
    - Explore opportunities to boost sales in lower-performing categories like Beauty products and Books.
4. Optimize Payment Methods:
    - Ensure credit cards usage is supported more in North America.
    - Promote debit card usage in Asia and expand PayPal options in Europe.
5. Highlight Top-Selling Products:
    - Feature bestsellers like Canon EOS R5 Camera and LG OLED TV in marketing campaigns.
    - Ensure sufficient stock of top-selling items to meet demand

### Limitations
---
1. The study relies on a dataset from a single source (Kaggle), which may not fully represent all global transactions. This limitation affects the generalizability of the findings to broader market conditions.
2. The analysis of payment methods is limited to three options (credit card, debit card, PayPal), potentially overlooking other significant payment methods used in various regions. This limitation might skew the understanding of regional payment preferences.

### References
---
  - Online Sales Dataset - Popular Marketplace Data. Kaggle.com. [link](https://www.kaggle.com/datasets/shreyanshverma27/online-sales-dataset-popular-marketplace-data)
