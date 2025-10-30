# Marketing-Campaign-Performance-Analysis
  A Digital  marketing campaigns across different channels: Email, Instagram Ads, and  Influencer Marketing.

  ## PROJECT OVERVIEW
  This Power-Bi project provides a comprehensive performance across multiple channels. Using card visual, chat, slicers, and DAX measures, I created a highly interactive, professional dashboard to track KPIs and help optimize strategies.
 
  ![image alt](https://github.com/Chisom965/Marketing-Campaign-Performance-Analysis/blob/de35372089dd1b2bf499703ea00c8cb1c73bd2b4/PBI%20Marketing%20Campaign%20Performance%20Analysis.png)

## Objective
   The primary goal of this analysis is to generate actionable insights in to the marketing campaign performance by Evaluating:
   
    1.Campaign performance across channels. 
    
    2.Track key marketing metrics.
    
    3.Optimizie decision making through data insights.
  
  
## Key Performance questions
1.Which marketing channel delivers the highest ROI? 

2.How does ad spend relate to impressions, clicks, and conversions across channels?

3.Which product or category generates the most revenue?

4.What is the overall conversion rate and how does it vary by channel or campaign?

5.How have key metrics (spend, conversions, revenue, ROI) changed over time?

6.Which campaigns are underperforming and need optimization? 

7.What is the click-through rate (CTR) trend across platforms?

8.Which marketing strategy yields the best cost-efficiency (lowest cost per conversion)?

## Tools and methodologies
  "Tools used" Microsoft Power BIhttps:(//www.microsoft.com/en-us/power-platform/products/power-bi)
  
## Techniques
1.Data Cleaning and Transforming using Power Query.

2.Data KPI Creation.

3.Data Visualization for interactive and insightful dashboard.

4.Project Documentation for clear reporting of insights.

# Data Processing

## Data Importation and cleaning

Data was ingested using power BI Excel connector.

## Cleaning Steps
•	Previewed the Dataset in Excel Workbook.

•	Imported Dataset from Excel into Power Query Editor.

•	Checked for inconsistencies, errors, and duplicates.

•	Applied transformations and loaded clean data for visualization.

## Calculated Fields(DAX):
•	CTR= DIVIDE (SUM('PBI_Marketing_Data xlsx - marketing'[Clicks]), SUM('PBI_Marketing_Data xlsx - marketing'[Impressions]), 0) * 100

•	Conversion Rate=  DIVIDE(SUM('PBI_Marketing_Data xlsx - marketing'[Conversions]), SUM('PBI_Marketing_Data xlsx - marketing'[Clicks]), 0) * 100

•	Double Check ROI=  DIVIDE(SUM('PBI_Marketing_Data xlsx - marketing'[Revenue (INR)]) - SUM('PBI_Marketing_Data xlsx - marketing'[Ad Spend (INR)]), SUM('PBI_Marketing_Data xlsx - marketing'[Ad Spend (INR)]), 0) * 100

 ![image alt](

  
