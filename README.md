# My-PALMORIA-Documentation

This marks the beginning of my portfolio-building journey, which I've undertaken alongside my Data Analysis class at the Incubator Hub.  


Through this experience, I've gained valuable skills in various tools, including MS Excel, PowerBi and SQL. Now, I'm excited to apply these skills to build a strong portfolio that showcases my abilities.
## Project Topic: Capstone project Amazon Product Review Analysis
### Project overview
I am working The Palmoria Group, a manufacturing company based in Nigeria, is embroiled in issues bordering on gender inequality in its 3 regions. Unfortunately, the media recently published the news with the headline “Palmoria, the Manufacturing Patriarchy”. This doesn’t look good for the owners of the business, based on their ambition to scale the business to other regions and even overseas. Cases like this can only spiral downwards,revealing other issues like the gender pay gap, amongst other possible issues.The CEO of Palmoria, Mr Ayodeji Chukwuma, is keen to address these issues before they get out of hand. The CHRO, Mr Yunus Shofoluwe, has been assigned the task to identify key areas within the business that could give rise to issues and address them immediately.Mr Shofoluwe decided to recruit me as an HR Analytics expert to analyse the company’s HR data and come up with recommendations for management’s attention. “Now, the future of gender equality in Palmoria lies in your hands” – the exact words of Mr Shofoluwe before he handed the data to me.


### Dataset Description 
-    The dataset contains information including:
-    genders, regions,Bonus rate, departments,departments rating,salary and ratings etc.

-    Customer engagement: user reviews, titles, and content

-    Total Records:946rows
-    Each row represents a unique product, with aggregated reviewer data stored as comma-separated values


### Tools used
 - Ms Excel for Data cleaning [dowload Here](Http://www.microsoft.com)
    - For Data collection
    - For Data Cleaning
       - Data manipulation
       - Data munching
 
 - Power BI (Forcasting a report)[dowload Here](https://www.microsoft.com/en-gb/power-platform/products/power-bi/).

   
###  Explanatory Data Analysis 
-   The EDA involves exploring of the Data to answer some questions like:
-  Analysis Tasks
  -   What is the gender distribution in the organization? Distil to regions and departments

  -   Show insights on ratings based    gender

  -   Analyse the company’s salary structure. Identify if there is a gender pay gap. If there is, identify the department and regions that should be the focus of management

  -   A recent regulation was adopted which requires manufacturing companies to pay employees a minimum of $90,000

  -   Does Palmoria meet this requirement?

  -   Show the pay distribution of employees grouped by a band of $10,000. For example:

  -   How many employees fall into a band of $10,000 – $20,000, $20,000 – $30,000,etc.?

  -   Also visualize this by regions

###   DATA ANALYSIS 

  -     This is where we included the our data, chart and pivot table for formatting, filtering and columns calculations
  -     Task-by-Task Power Pivot Execution:
####  Task 1: Average Discount % by Product Category
  -     Insert Pivot Table using Data Model
  -     Rows: Main Category
  -     Values: discount_percentage (set to Average)
  -     Format values as Percentage
  -     Task 2: Product Count by Category
  -     Rows: Main Category
  -     Values: product_name (set to Distinct Count)
###   Task 3: Total Reviews per Category
  -     Rows: Main Category
  -     Values: rating_count (set to Sum)
###   Task 4: Products with Highest Ratings
  -     Rows: product_name
  -     Values: rating (set to Average)
  -     Sort Descending by Rating
  -     Optional: Filter to show Top 10
###   Task 5: Average Actual Price vs Discounted Price by Category
  -     Rows: Main Category
  -     Values: actual_price (set to Average)
  -     Values: discounted_price (set to Average)
###   Task 6: Products with Most Reviews
  -     Rows: product_name
  -     Values: rating_count (set to Sum)
  -     Sort Descending by Review Count
###   Task 7: Products with 50% or More Discount
  -     Rows: High Discount
  -     Values: product_name (set to Count)
###   Task 8: Distribution of Product Ratings
  -     Rows: rating
  -     Values: product_name (set to Count)
###   Task 9: Total Potential Revenue by Category
  -     Rows: Main Category
  -     Values: Potential Revenue (set to Sum)
###   Task 10: Unique Products per Price Range Bucket
  -     Rows: Price Range Bucket
  -     Values: product_name (set to Distinct Count)
###   Task 11: Rating vs Discount Level
  -     Rows: discount_percentage (optional: group into bands)
  -     Values: rating (set to Average)
  -     Optional: Create scatter plot for visual relationship
###   Task 12: Count of Products with < 1,000 Reviews
  -     Rows: Low Reviews
  -     Values: product_name (set to Count)
###   Task 13: Categories with Highest Discounts
  -     Rows: Main Category
  -     Values: discount_percentage (set to Average)
  -     Sort Descending
###   Task 14: Top 5 Products by Combined Score
  -     Rows: product_name
  -     Values: Combined Score (set to Sum)
  -     Sort Descending
  -     Filter Top 5
  - 

  ##  RESULT_FINDINGS
  -    I uncovered that the product with the highest number of reviews is the Amazon basics wireless (high_speed cable)with 91-100% point , this gives us a feedback of user satisfaction.
  -   we also have the Toys and Games Category with the lowest Revenue, as it's a less demanded and highly dependent on the seasonal and August events.

  ##  RECOMMENDATION 

  -   I recommend strongly that Amazon companies should consider carrying out market surveys,using both primary data and secondary to make decisions that are satisfactory to its customers,Hence, increases the company's revenue.
  -   we understand that customers and pricing play a large role to translate available products into Revenue.

  ##  LIMITATIONS 
  -   One of the major limitations is seasonality in amongst many of the company's products
  -   Poor marketing strategies, and customer engagement.
  -   Customer Relationship Management Technology is bias and not properly optimized  

##   REFERENCE 
 -    https://github.com/Dambos01/My-DSA-Documentation/edit/main/README.md
 -    Amazon
 -    Idowu oluwagbenga oluwatubosun 

 
