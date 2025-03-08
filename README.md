![banner](assets/Banner_BikeSales_Dataset.png)  
Banner <a href="https://www.istockphoto.com/photos/bicycle-for-sale" target="_blank">source</a>

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

Badge <a href="https://shields.io/" target="_blank">source</a>

# Key Findings: Bike Sales Dataset

1. Data Cleaning and Preparation:

- Duplicates Removal: All duplicate entries were identified and removed to ensure data accuracy and prevent skewed results.
- Subject Standardization: Applied consistent naming conventions by finding and replacing variations in subject fields.
- Currency Formatting: Removed decimal points from currency-related data to enhance readability and ensure uniform formatting.


2. Pivot Table Analysis:
- Average Income per Purchase by Gender:
  - Analyzed the average income of customers based on their purchases, split by gender (Male and Female).
  - Provided insights into how income levels impact purchasing behavior for both genders.

- Customer Commute Analysis (Distance vs. Purchase Behavior):
  - Segmented customers by their commuting distance from home (0-1 miles, 1-2 miles, 2-5 miles, 5-10 miles, and more than 10 miles).
  - Compared whether customers in each distance bracket purchased a bike (Yes/No).
  - This analysis helped identify trends between commuting distances and bike purchases.

- Customer Age Brackets and Bike Purchases:
  - Grouped customers into age brackets: Adolescents, Middle Age, and Old.
  -Examined which age groups were more likely to purchase a bike and which were not, providing insights into age-related buying behavior.

- Purchase Count by Age:
  - Generated a detailed count of bike purchases based on age, with clear differentiation between customers who purchased and those who did not, showing a grand total for each age group.

3. Dashboard Visualizations:

A user-friendly dashboard was designed to present the findings in a clear and interactive manner, covering the following metrics:

- Average Income Per Purchase:
  - A visual representation of the average income for customers who purchased bikes, broken down by gender for a quick comparison.

- Customer Age Brackets:
  - Illustrated the age distribution of customers, highlighting the purchasing patterns of each age group (Adolescent, Middle Age, Old).

- Customer Commute and Purchase Correlation:
  - A chart showing the relationship between customer commuting distances and their likelihood of purchasing a bike.

4. Interactive Dashboard Slicers:

The dashboard includes interactive slicers, allowing users to filter data based on the following criteria:

  - Marital Status: Married vs. Single
  - Region: Europe, North America, and Pacific
  - Education Level: Bachelors, Graduate Degree, High School, Partial College, and Partial High School


<!-- Authors -->
<!-- ## Reference
- Learn 80% of Data Analysis in Excel in Just 12 Minutes ( https://www.youtube.com/watch?v=O1QfG5SXRkM) -->

## Table of Contents

  - [Key Findings: Bike Sales Dataset](#key-findings-bike-sales-dataset)
  - [Table of Contents](#table-of-contents)
  - [Business Problem](#business-problem)
  - [Data source](#data-source)
  - [Methods](#methods) 
  - [Tech Stack](#tech-stack)
  - [Summary of Key Results](#summary-of-key-results)
  - [Lessons Learned and Recommendation](#lessons-learned-and-recommendation)
  - [Limitation and What Can Be Improved](#limitation-and-what-can-be-improved)
  - [Run Locally](#run-locally)
  - [Repository Structure](#repository-structure)
  - [Contribution](#contribution)
  - [License](#license)

## Business Problem
The company is facing challenges in understanding which demographic factors most influence bike sales, leading to inefficient marketing efforts and missed sales opportunities. By analyzing customer data—such as income, age, commute distance, and purchasing behavior—the goal is to identify key trends that impact bike purchases. Specifically, we seek to determine how income levels, commuting distances, age brackets, marital status, education, and regional factors influence a customer’s decision to buy a bike. This will help the company understand which segments (e.g., commuters, high-income earners, or specific age groups) are most likely to purchase, allowing for more targeted marketing efforts.

Gaining these insights will enable the company to optimize its marketing campaigns, focusing on high-potential customer groups, which can lead to higher conversion rates and sales growth. Additionally, understanding the relationship between customer demographics and purchasing behavior will guide product development and promotional strategies, improving the company's ability to meet customer needs, expand its market share, and increase profitability.

## Data Source

- Full Project in Excel | Excel Tutorials for Beginners (https://www.youtube.com/watch?v=opJgMj1IUrc&t=388s)

## Methods

1. Data Cleaning and Preparation:
  • Removing Duplicates
  • Finding and Replacing Subjects
  • Removing Decimals - Currency

2. Exploratory Data Analysis (Pivot Table):
  • Average Income Per Purchase (by Gender)
  • Customer Commute Analysis
  • Customer Age Brackets
  • Count of Bike Purchases by Age

3. Data Visualization and Dashboarding:
  • Dashboard Creation
  • Slicers

## Tech Stack

- Microsoft Excel
  - Data Cleaning (Removing Duplicates, Find and Replace, Currency Formatting)
  - Pivot Tables
  - Dashboard Creation
  - Slicers


## Summary of Key Results

Working Sheet

![Working Sheet - Bike Sales Dashboard](assets/WorkingSheet_BikeSales_Dataset.png)

Average Income Per Purchase (Male and Female)

![Statistics - Descriptive - Fastfood Restaurant](assets/Statistics_Descriptive_FastFoodRestaurant.png)

Customer Commute Analysis: Purchase Behavior by Distance (0-1 Miles, 1-2 Miles, 2-5 Miles, 5-10 Miles, and More than 10 Miles)

![Questions - Fastfood Restaurant](assets/Questions_FastFoodRestaurant.png)

Customer Age Brackets (Adolescent, Middle Age, Old): Bike Purchase vs. Non-Purchase Analysis

![Pivot Table - Bestselling Prodcut - Fastfood Restaurant](assets/PivotTable_BestsellingProduct_FastFoodRestaurant.png)

Count of Bike Purchases by Age: Purchased vs. Not Purchased (Including Grand Total)

![Pivot Table - Revenue - Fastfood Restaurant](assets/PivotTable_Revenue_FastFoodRestaurant.png)

Dashboard
  - 1. Average Income Per Purchase
  - 2. Customer Age Brackets
  - 3. Customer Commute

![Pivot Table - ManagerRevnue - Fastfood Restaurant](assets/PivotTable_ManagerRevenue_FastFoodRestaurant.png)

Slider
  - 1. Married and Single
  - 2. Region: Europe, North America and Pacific
  - 3. Education: Bachelors, Graduate Degree, High School, Partial College and Partial High School

![Pivot Table - ManagerRevnue - Fastfood Restaurant](assets/PivotTable_ManagerRevenue_FastFoodRestaurant.png)





## Lessons Learned and Recommendation
Through data analysis, it was found that best-selling products like Burgers, Fries, and Beverages drive significant revenue, suggesting a focus on product-specific promotions. Payment methods also impact revenue, with different patterns observed for cash, credit cards, and gift cards, guiding tailored payment strategies.

Performance varies by manager and country, indicating the importance of region-specific strategies to enhance efficiency. Box and whisker plots revealed insights into price distribution, helping to refine pricing by identifying optimal price ranges and outliers.

Recommendation: 
  1. Focus on Top Products: Prioritize marketing and upsell strategies for best-selling items like Burgers and Beverages, which contribute most to revenue. Customization of promotions can further boost these product categories.

  2. Optimize Payment Systems: Tailor payment strategies to maximize revenue, encouraging the use of high-revenue payment methods (e.g., credit cards) through loyalty programs or incentives for gift card usage.

  3. Manager and Regional Performance: Implement regular performance assessments across managers and regions to address underperformance. Introduce regional-specific strategies that account for local preferences and market conditions.

  4. Refine Pricing Strategies: Use descriptive statistics and data visualizations to continuously evaluate product pricing. Adjust prices to stay competitive while maintaining profit margins, focusing on outliers and price sensitivity.

  5. Continue Data-Driven Decision Making: Leverage pivot tables and visualization tools to further analyze trends, identifying new opportunities for product improvement, cost management, and revenue growth.

## Limitation and What Can Be Improved

Limitations
- The analysis was limited by Excel’s capacity for handling large datasets and lacked insights into individual customer behavior or external factors like seasonality and market trends.

Improvements
- Future analysis could benefit from using tools like Power BI or Tableau for more detailed insights. Incorporating customer segmentation and external data (e.g., competitor pricing) would improve decision-making.


## Run Locally
Initialize git

```bash
git init
```


Clone the project

```bash
git clone https://github.com/johncanero/fastfood_chain_dataset_john_canero.git
```

enter the project directory

```bash
cd fastfood_chain_dataset_john_canero
```

Open in Visual Studio Code

```bash
code .
```

## Repository Structure


```
├── assets
│   ├── Banner_FastFoodRestuaurant_Dataset.png      
│   ├── PivotTable_BestsellingProduct_FastFoodRestaurant.png 
│   ├── PivotTable_ManagerRevenue_FastFoodRestaurant.png
│   ├── PivotTable_Revenue_FastFoodRestaurant.png   
|   ├── Questions_FastFoodRestaurant.png 
│   ├── Statistics_Descriptive_FastFoodRestaurant.png
|   ├── WorkingSheet_FastFoodRestaurant.png
|
|
├── 02_fastfood_chain_dataset_john_canero.xlsx
│ 
│
├── README.md                     
│
│
```

## Contribution

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change or contribute.

## License

MIT License

Copyright (c) 2022 Stern Semasuka

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Learn more about [MIT](https://choosealicense.com/licenses/mit




