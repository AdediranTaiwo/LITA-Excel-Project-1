# LITA-Excel-Project

## Excel Project 1 (Sales Data)

## Project Title: Sales Performance Analysis For a Retail Store Using Microsoft Excel.

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Analysis](#data-analysis)

### Project Overview: 
This project aims at analysing the sales performance of a retail store. Exploring sales data to umcover key insights such as top-selling products, regional performance and nonthly sales trends.

### Data Sources

The primary source of the Data used in his project is a sales Data of a retail store

### Tools Used
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. For Data Cleaning
  2. Data Analyxing
  3. Data Calculation using Pivot Tables

### Data Cleaning And Preparation

1. Data loading and Inspection
2. Hamdling missing Variables
3. Data Cleaning And Formating

### Exploratory Data Analysis
Exploratory Data Analysis involved the exploring of the Data to answer some questions about the Data such as;
- What is the summmary of Total Sale by ;
  1. Product
  2. Region
  3. Month
- What is the average sales of each of the products?
- What is the total revenue by region?

### Data Analysis 
#### Steps in acquaring my results: 
- Exploration of the available data
- Cleaning the data for effective analysis by removing the duplicates.
- Duplicates are removed by selecting the data range with the headers and clicking "Data" at the tool bar then move the cursur to " Remove Duplicate"
- selecting "All" option or specific column and clicking "ok"

  After cleaning the file, another column was created to calculate the Total Sales and the formula used in calculating it is Quantity* unit price. Double clicking on the first result gave me the results for the other columns. I then proceed to calculating the average sales for each of the products.

### Results

AVERAGE SALES PER PRODUCTS

- Average sales for shirts 326.5636
- Average sales for shoes  308.6965
- Average Sales for hat    158.8122
- Average  Sales for socks 121.8228
- Average sales for jacket  139.9395
- Average sales for Gloves  200.0674

### Data Visualization
```
PIVOT TABLE FOR SALES DATA PROJECT.xlsx
```


## Excel Project 2 (Customer Data)

### ABSTRACT

This report aims at analyzing customer data and understanding the subscription trends to know the best action to take for the subscription types not doing well. It presents an in-depth analysis of customer subscription service data, focusing on segmentation, cancellation trends, and overall subscription patterns. the analysis aims to understand customer behaviour, track subscription types, and identify key trends in cancellations and renewals. Using a combination of MS Excel, SQL, and Power BI, the data was cleaned, organized, analyzed, and visualized to reveal insights into customer behaviour.

### Objectives
- To analyze regional performance
- To understand the characteristics and preferences of different customer purchases
- To identify key trends in cancellations and renewals

###DATA INFORMATION
Data sources
The data used in this project was obtained from the Incubator Hub. It includes detailed records of transactions, customer demographics, subscription information and regional sales distribution.

### Data Collection
The data used was collected and complied through transaction logging. This ensures that the dataset represents an accurate record of customer interactions and purchasing patterns over time.

### Data Characteristics
The dataset includes the following variables:

- CustomerID : A uniques identification of each customer
- Customer Name : Names of the customers
- Region : The regions where the subscriptions occured
- Subscription Type : Type of subscription purchased
- Subscription Start: The date of subscription
- Subscription End : the date of subscription expiration
- Canceled : If the subscription was canceled or not
- Revenue : The revenue generated from each purchased
- Subscription Duration : The duration of each purchased subscription

### BASIC STATISTICS IN THE DATASET
- Total Revenue : 67.5 billion
- Average Duration : 365.35
- Total Customer : 33787
- Total Order : 33787

### METHODOLOGY
- Data Cleaning
- Removing duplicates Eliminated duplicated records to ensure Data Quality

Adding New Columns: Added new columns sales and revenue by multipling the quantity of the product purchased by the respective unit price, added a column for average subscription duration of the types of subscription purchased.

### EXPLORATORY DATA ANALYSIS (EDA)
After cleaning the data in excel and making pivot tables for analysis, it was exported to SQL for further analysis and finally to power BI for creation of dashboard. The following were carried out:

- Excel Analysis : Used for initial exploration and basic calculations.
- Data Preparation
- Data cleaning : Eliminated duplicated records to ensure Data Quality.
- New columns calculated : Calculated the time between subscription start and subscription end date for each subscriber.
- Basic Subscription Statistics
- Summary table : Presented subscriber count, average subscription duration, average monthly revenue, and most popular subscription type.
Customer Distribution and Segmentation
- Subscription count by type : Created pivot tables to display counts for each subscription type (e.g., monthly, quarterly, annual)
- Subscriber segmentation : used pivot tables to segment subscribers based on activity (retained, canceled)

### Data Visualization
