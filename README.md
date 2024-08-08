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
This project conducts an exploratory analysis of failed banks in the United States from 2000 to 2024, examining the total number of failures by state, year, and month. It identifies trends, generates data-driven insights, and provides recommendations for future improvements.

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
  1.  What is the total number of failed banks, and the total number of states that experienced bank failures?
  2.  Which of the states recorded the highest number of bank failures?
  3.  Which year recorded the highest number of bank failures?
  4.  Is bank failure more common in any particular month of the year?
  5.  Which state did not experience any bank failures?

### Data Analysis
---
#### 1.  What is the total number of failed banks, and the total number of states that experienced bank failures?
  - To answer the questions the following were done. 
    - New measures were created for *total Banks* and *total sales*
    - Consequently, visual cards were used to present it on the dashboard.

<img width="287" alt="Screenshot 2024-08-07 135129" src="https://github.com/user-attachments/assets/6be90f7e-fff1-456f-a02c-9af061bd84f0">

      
<img width="200" alt="Screenshot 2024-08-07 134934" src="https://github.com/user-attachments/assets/d62c3135-4091-4bf9-958e-85426317508a">

<img width="200" alt="Screenshot 2024-08-07 135017" src="https://github.com/user-attachments/assets/be8fcfcc-3cbd-4fc7-80a2-f1f3fd84202a">

#### 2.  Which of the states recorded the highest number of bank failures?
  - The following barchart is used to answer the question

<img width="350" alt="Screenshot 2024-08-07 134703" src="https://github.com/user-attachments/assets/98daa304-bfac-4738-bab4-d98f1e87597b">

#### 3.  Which year recorded the highest number of bank failures?
  - To answer this, the following steps were taken
    - *Date table* was created first to generate year, after which a column chart visual was created as shown below.

<img width="352" alt="Screenshot 2024-08-07 134739" src="https://github.com/user-attachments/assets/27177cab-9237-400c-8f89-cfe14204a69e">

#### 4.  Which month(s) experienced significantly higher bank failures compared to others?
  Using the date table, month column was generated. Thus, the column chart below is used to answer the question,

<img width="433" alt="Screenshot 2024-08-07 134800" src="https://github.com/user-attachments/assets/d83a17b0-88f2-425a-b208-5e20d33c692b">

#### 5.  Which state did not experience any bank failures?
  The Shape map below is used to answer the question. States with colour white did not experience bank failure.

<img width="433" alt="Screenshot 2024-08-07 134833" src="https://github.com/user-attachments/assets/a177887d-8210-4e25-a2a9-22f015bc9f50">


### Findings
---
#### Summary of results.

<img width="879" alt="Screenshot 2024-08-07 133745" src="https://github.com/user-attachments/assets/b2e73a58-1e07-4efd-be0d-0d5c4c19b173">

  - The total number of failed banks was 569, spread across 44 states.
  - Georgia (GA) recorded the highest number of bank failures, with 93.
  - The year 2010 had the highest number of bank failures, totaling 157.
  - Bank failures were significantly higher in April(61), July(75), and October(63).
  - Seven states (Montana [MT], North Dakota [ND], Delaware [DE], Vermont [VT], Maine [ME], Rhode Island [RI], and Alaska [AK]) did not experience any bank failures.


### Recommendations
---
1. Strengthen Regulatory Oversight: Focus on states like Georgia with high bank failure rates. Implement     stricter regulatory measures to monitor and manage banks' health and stability.
2. Improve Risk Management: Encourage banks to adopt robust risk management practices to mitigate factors    leading to failures. This includes better credit risk assessment, liquidity management, and capital       adequacy.
3. Enhanced Monitoring During High-Risk Periods: Given that bank failures were more common in April,         July, and October, regulatory bodies should increase monitoring and support for banks during these        months.
4. Regional Support Programs: Establish support programs in states with higher failure rates to assist       struggling banks, such as financial aid packages, restructuring advice, or temporary management           interventions.
5. Investigation and Learning: Conduct detailed investigations into the causes of bank failures in           high-risk states and years. Use the findings to inform policy and regulatory adjustments.
6. Public Awareness and Education: Increase public awareness about the factors leading to bank failures      and how to identify early warning signs. Educate bank management and stakeholders on best practices to    prevent failures.


### Limitations
---
1. Data Constraints: The study relies on historical data which may not capture all relevant variables        affecting bank failures. Factors such as macroeconomic conditions, market trends, and policy changes      may also play a significant role.
2. Geographical Variations: The study does not account for regional economic differences that might          influence bank stability. Economic conditions in Georgia may be different from those in states with       fewer failures.
3. Temporal Changes: The financial landscape changes over time. Practices that led to failures in 2010       may differ from those that could cause future failures. The findings might not be directly applicable     to current or future banking environments.
4. Limited Scope: The research focuses on failed banks and states but does not consider the impact on the    broader economy, communities, or stakeholders affected by these failures.


### References
---
  - Federal Deposit Insurance Corporation (FDIC) Failed Banks List. [link](https://catalog.data.gov/dataset/fdic-failed-bank-list).
