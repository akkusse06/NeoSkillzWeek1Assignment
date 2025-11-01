# 🛒 Superstore Sales Dataset Analysis (2011-2015)
## 📊 Overview

The **Superstore Sales Dataset (2011-2015)** is a comprehensive dataset stored in an Excel file (`Superstore.xlsx`) that captures 25,035 unique orders from 1,590 customers across various regions, categories, and sub-categories, with total sales of $12.64 million and profits of $1.47 million. 

The dataset is organized into four sheets: the main **superstore_dataset2011-2015** sheet (~51,290 rows) contains detailed transactional data with columns like Order ID, Sales, Profit, Customer ID, and Region; the **Customers** sheet lists customer details; the **Pivot Tables** sheet summarizes sales, profit, and quantity by year, region, and category; and the **Dashboard** sheet provides a regional overview. 

### Key Excel formulas enhance the dataset’s utility:
- **VLOOKUP** retrieves customer names from the Customers sheet by matching Customer IDs  
- **SUMIF** aggregates sales or profit by region or customer ,                                                                       
- **IF** assigns Sales Status like "Low" ,"Medium"or "High" based on sales thresholds ;                                                                         
- **MAX** identifies the highest sales or profit;                                                                                          
- **MIN** finds the lowest sales and profit                                                                                                                  
- **AVG** calculates average sales or profit.                                                                                                         
- **COUNTIF** to count based on condition country

### Key insights
- Technology leads in sales, but Office Supplies has high profit efficiency.                                                                                         
- Furniture has negative profit in the Tables sub-category (-$64K)
- Central dominates with 22% of sales and the highest profit.
- Africa & Southeast Asia have lower profit margins.
- Steady growth: Sales ↑90% from 2011-2014.
- Ship Mode: Standard Class (most common, avg. sales $246).
- Discount Impact: Higher discounts correlate with lower profits.
- Order Priority: Critical orders have higher avg. sales ($134/same day)
