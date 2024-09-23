# Email-Performance-Power-BI-Dashboard
Project description

This project is focused on developing an Email Performance Dashboard for the marketing team using Power BI, SQL, and Excel. The dashboard provides insights into email campaigns, tracking the number of emails sent daily, weekly, and termly, along with conversion rates (CR). It is designed to help the marketing team evaluate email performance across various regions and countries, and enables the creation of new KPIs and matrices for future campaigns.

Technology Stack

Power BI: Used for data visualization and creating the dashboard with dynamic reporting.
SQL: Employed to query email data from internal databases, supporting complex filtering and grouping operations.
Excel: Utilized for pre-processing data, importing certain metrics, and integrating with Power BI for seamless analysis.

Key Features

Email Activity Tracking: Visualizes the number of emails sent daily, weekly, and termly, allowing for easy monitoring of campaign activity over time.
Conversion Rate (CR) Analysis: Provides detailed conversion rate metrics for each period, helping to assess campaign effectiveness.
Geographical Insights: Tracks email activity and conversion rates by region and country, enabling deeper analysis of regional performance.
Custom KPIs and Matrices: Allows the marketing team to create and measure custom Key Performance Indicators (KPIs) and matrices tailored to specific campaign goals.
Performance Filtering: Offers advanced filtering capabilities for divisional, regional, and campaign-specific performance, empowering users to drill down into specific data sets.
How It Works


Data Source: 

SQL queries pull email data from internal databases and export it to Excel for any additional calculations.
Pre-processing: Excel is used for data cleaning and pre-processing, ensuring that metrics like dates, regions, and email statuses are accurate.
Dashboard Creation: Power BI takes the processed data, building dynamic reports that allow users to track emails and conversion rates across various timeframes and geographical segments.
Insight Generation: The dashboard enables the marketing team to generate insights from historical email data, optimize campaign strategies, and evaluate geographical performance.


Usage
To view or modify the dashboard, ensure that you have access to:

The email data via your SQL database.
Pre-processed data files from Excel.
Power BI Desktop for viewing or editing the dashboard.
Once the data is set up, you can:

Load the data from SQL and Excel into Power BI.
Use the built-in filters and slicers to analyze specific periods (daily, weekly, or termly) or regions.
Adjust or add new KPIs/matrices for more refined insights.
Future Enhancements
Automation: Automate the data refresh process using Power BI’s scheduling features to ensure real-time reporting.
Predictive Analysis: Implement machine learning models to predict future email campaign performance and conversion rates.
Screenshots

![image](https://github.com/user-attachments/assets/ae3bfe5e-9a0b-4f41-a6fb-0c2be2427255)

![image](https://github.com/user-attachments/assets/093ba8d2-5a98-4aba-aa91-fecaa285c2b2)

Data Modeling:
This Power BI data model integrates various datasets such as Region, Country, and Degree with detailed email and applicant data like Sent email (T4), Received email (T4), and Active applicants. It connects key attributes like Admissions Advisor, Applicant ID, and Team KPIs, enabling detailed tracking of performance metrics and applicant engagement across regions and teams. This structure ensures efficient reporting, filtering, and cross-functional analysis to drive admissions and performance insights.
![image](https://github.com/user-attachments/assets/ae15c23e-fb99-4c11-88cb-4c4ccbdd2251)

