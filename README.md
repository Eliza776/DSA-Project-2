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
Amazon Product Review Analysis               

## Project Overview
This project is a comprehensive Excel-based analysis of Amazon product data, covering pricing patterns, discount distribution, customer reviews, and category-level metrics.  
It includes pivot tables, calculated columns, and an interactive dashboard for actionable business insights.

## Data Source
The dataset contains information scraped from Amazon product pages.

## Tools Used
- Power BI (Charts, filters,slicers)  – [Download here](https://www.microsoft.com)
  - For data collection
  - For data cleaning
  - For visualization

## Data Cleaning
In the cleaning process, I began with a thorough check of the raw dataset to identify issues such as:
-Replaced missing gender entries with "Undisclosed"

-Removed employees without salary (assumed exited)

-Removed records with "NULL" department entries

-Merged and processed bonus allocation dataset (based on rating)

-Derived columns: Salary bands, total pay, bonus amount




## Explanatory Data Analysis
EDA involved answering key questions about the dataset to uncover gender disparities and compliance status . These questions included:

 -Gender Distribution

  -Overall, by region, and by department

-Performance Ratings by Gender

  -Compare average ratings and counts

-Salary Structure & Pay Gap

  -Average salary by gender

 -Gender pay gap by department and region

-Salary Regulation Compliance

  -Number of employees earning below $90,000

   -Salary bands distribution ($10,000 increments)

  -Breakdown by region

-Bonus Pay Allocation

  -Individual employeee bonus

   -Total payout per employee

  -Total payouts by region and company-wide

.

## Data Analysis
This section outlines some of the key queries and functions applied during the analysis phase:

- `IF` – to derive bonus amount based on employee rating
- `AVERAGE` – to compute average salary by gender, and  average rating by gender
- `COUNT` – for counting numbers of employees 
   

## My Analysis
- The gender balance is almost equal across the organization, but the undisclosed gender group still makes up over 4%, which may hinder exact figure in gender analysis
-Lagos has a relatively balanced number.
-Kaduna has a higher number of males compared to females.
-Abuja also shows a higher number of  male employees.
-Performance ratings are fairly distributed across genders.
-Male and Female employees appear to earn nearly the same total salary value, which indicates pay equality.
-The largest group of employees earns $70,000–$80,000, falling below the $90K compliance mark.
-Kaduna and Abuja are non-compliant to the salary regulation.
- Kaduna has the highest number of employees earning below $90,000,followed by Abuja, and then Lagos with the least number.
  
## Visualizations






  



  
## My Recommendation
This project helped me develop practical skills in data cleaning, analysis, and visualization using Excel. I discovered how to interpret raw product data and convert it into meaningful business insights.  
My key takeaways are ;
-The business should invest more in Electronics and Computer Accessories as they show the highest revenue potential.
- High discounts (91–100%) are associated with higher ratings, the business should consider offering limited-time high discounts to boost product visibility and customer reviews especially for products generating less revenue.
