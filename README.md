# DSA-Project-2

## Table of Contents
- [Project Topic](#project-topic)
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Cleaning](#data-cleaning)
- [Explanatory Data Analysis](#explanatory-data-analysis)
- [Data Analysis](#data-analysis)
- [My Analysis](#my-analysis)
- [Visualization](visualization)
- [My Recommendation](#my-recommendation)
  

## Project Topic
Palmoria Group HR Analysis               

## Project Overview
A data-driven HR analysis for Palmoria Group to uncover inequality, salary gaps, and performance trends, with actionable insights for organizational equity and compliance.

## Data Source
The dataset contains information scraped from Palmoria group pages.

## Tools Used
- Power BI (Charts, filters,slicers)  – [Download here](https://www.microsoft.com)
  - For data collection
  - For data cleaning
  - For visualization

## Data Cleaning
In the cleaning process, I began with a thorough check of the raw dataset to identify issues such as:

 -Replaced missing gender entries with "Undisclosed"

 -Removed employees without salary

 -Removed records with "NULL" department entries

 -Merged and processed bonus allocation dataset (based on rating)

 -Derived columns: Salary bands, total pay, and bonus amount




##  Explanatory Data Analysis

EDA involved answering key questions about the dataset to uncover gender disparities and compliance status. These questions included:

- **Gender Distribution**
  - Overall gender breakdown
  - Gender distribution by region
  - Gender distribution by department

- **Performance Ratings by Gender**
  - Compare average performance ratings by gender
  - Count of performance ratings across genders

- **Salary Structure & Pay Gap**
  - Average salary by gender
  - Gender pay gap by department
  - Gender pay gap by region

- **Salary Regulation Compliance**
  - Number of employees earning below $90,000
  - Salary distribution grouped in $10,000 increments
  - Salary compliance breakdown by region

- **Bonus Pay Allocation**
  - Bonus calculation per individual employee (based on rating)
  - Total earnings (salary + bonus) per employee
  - Total bonus payout by region and company-wide



## Data Analysis
This section outlines some of the key queries and functions applied during the analysis phase:

- `IF` – to derive bonus amount based on employee rating
- `AVERAGE` – to compute average salary by gender, and average rating by gender
- `COUNT` – to count number of employees 
   

## My Analysis
 1. The gender balance is almost equal across the organization, but the undisclosed gender group still makes up over 4%, which may hinder exact figure in gender analysis

 2. Lagos has a relatively balanced number.

 3. Kaduna has a higher number of males compared to females.
 
 4. Abuja also shows a higher number of  male employees.
    
 5. Performance ratings are fairly distributed across genders.
    
 6. Male and Female employees appear to earn nearly the same total salary value, which indicates pay equality.
  
 7. The largest group of employees earns $70,000–$80,000, falling below the $90K compliance mark.
    
 8. Kaduna and Abuja are non-compliant to the salary regulation.
    
 9. Kaduna has the highest number of employees earning below $90,000,followed by Abuja, and then Lagos with the least number.
  
## Visualizations






  



  
## My Recommendation
-A salary review should be done in Kaduna and Abuja, where non-compliance is most severe.
-Gender distribution varies by region. Kaduna and Abuja may require to hire more females
-Enable gender disclosure for the undisclosed with suggested  privacy protections for more accurate analysis.
-A large portion of the workforce (over 50%) falls below the $90,000 threshold, fewer than 300 employees earn above $120,000 out of a total number of 946 employees. 


