# Capital-Expenditure-Investments-Analysis


![Power BI](https://img.shields.io/badge/Analytics-Power_BI-yellow?logo=powerbi&logoColor=white&style=flat-square) <br>
![VBScript](https://img.shields.io/badge/Scripting-Visual_Basic-blue?logo=visual-studio&logoColor=white&style=flat-square) <br>
![OneDrive for Business](https://img.shields.io/badge/Cloud-OneDrive_for_Business-blue?logo=onedrive&logoColor=white&style=flat-square) <br>
![Microsoft Teams](https://img.shields.io/badge/Communication-Microsoft_Teams-purple?logo=microsoft-teams&logoColor=white&style=flat-square) <br>


<hr style="border: 2px solid gray;">

### Project Objective
---

This initiative focuses on enhancing transparency regarding allocated budgets and real-time expenditure by different departments and divisions within the organization. Utilizing Power BI and DAX measures, the estimated expenditures were computed with valuable insights contributed by Financial Control representatives, factoring in various financial model considerations.

The report delves into historical spending patterns related to past projects, facilitating the prediction of future budgets for extended investment strategies. Serving as a catalyst, this report prompts monitored departments to execute timely liquidations, fostering progress on their projects and elevating overall productivity within the organization.



### Dataset Information
---

This dataset, obtained through VBS scripting from SAP, provides near real-time data. Historical reports, generated using for loops, enable ongoing monitoring of expenditures on long-term projects against annual budgets. Project budgets are adjusted at year-end to meet project needs.

In a star schema format, dimension tables, including a Power BI hard-coded date table and divisional cost center details, are complemented by a fact table. I have also developed additional Power BI reports, presenting information on spending, forecasting, and comments from respective divisions, particularly in cases of significant over or underspending.


### Project Approach
---

To achieve the project objective, the following ETL and Power BI report development steps were followed....

**1. Data Extraction:**
Used Visual Basic Scripting and for loops to extract historical data from SAP efficiently, reducing report sizes and minimizing the risk of session timeouts by extracting data per cost center.

**2. Data Transformation:**
The data is pre-processed in Excel Power Query to ensure that it is ready for analysis, since it is exported from SAP in text with tabs format, it requires some structuring, removal of system generated totals, removal of empty rows and columns, removal of special characters that interfere with data type conversions and appending. 

**3. Power BI report development:**
Employed Power BI to interface with the Excel Power Query output, crafting a customized report that aligns with user requirements. Developed measures and calculated columns using DAX, incorporating expert logic provided by Finance specialists to generate realistic forecasts based on diverse factors.



### The Resultant Power BI reports
---

<p align="center">
  <img src="https://github.com/CarolMmai/Capital-Expenditure-Investments-Analysis/blob/main/CAPEX_Investment_report.gif" width="800" height="450" alt="CAPEX_Investment_report">
</p>

<br>

<p align="center">
  <img src="https://github.com/CarolMmai/Capital-Expenditure-Investments-Analysis/blob/main/Network%20Project%20spend%20Power%20BI%20report.gif" width="800" height="450" alt="Late_product_delivery_Power_BI_report">
</p>


### Value added to the business
---
1. Budget Estimation: Tracking ensures consistent budget estimation at the group level, considering various financial factors.
2. Dynamic Project Management: Business divisions are prompted to adjust project spending, either accelerating or rolling over, based on their budget performance.
3. Savings Reallocation: Completed projects offer opportunities for savings, facilitating the reallocation of funds to other needed projects.
4. Cost Efficiency: Enables cost reduction on non-priority projects, minimizing wasteful expenditure.