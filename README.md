## Data Modeling and Analysis with Power Pivot and Power Query
- This project demonstrates how to perform data modeling and analysis using Microsoft Excel's Power Pivot and Power Query features. The goal of the project is to combine and analyze data from multiple sources (Orders, Products, and Customers) to generate valuable insights about sales performance, returning customers, and profit calculations.

### Project Overview
- In this project, I worked with three datasets:
  - Orders (Fact Table): Contains order-level data, including Order ID, Customer ID, Product ID, and Quantity.
  - Products (Dimension Table): Provides product information, including Product ID and Profit per Unit.
  - Customers (Dimension Table): Holds customer data, including Customer ID and customer details.

### Main Steps:
- Data Loading and Preparation:
  - Imported data using Power Query from three CSV files (Orders, Products, Customers).
  - Performed basic data cleaning (e.g., converting column headers, formatting fields).
  - Loaded the data into Excel’s Power Pivot data model.
    

### Data Modeling:
- Defined relationships between tables in Power Pivot:
  - Customer ID connects the Orders table with the Customers table.
  - Product ID connects the Orders table with the Products table.
  - Ensured relationships were set as many-to-one for proper data aggregation.
![Screenshot 2024-10-13 134326](https://github.com/user-attachments/assets/e4996e9d-35f7-4f2f-9964-3dc7bb009c37)

### Calculated Columns:
- Created a calculated column for Total Profit by multiplying the Profit per Unit from the Products table with the Quantity in the Orders table using the RELATED function.
- Added a Returning Customer Flag column to identify customers who have placed more than one order using the CALCULATE and COUNTROWS functions.
  ![Screenshot 2024-10-13 134408](https://github.com/user-attachments/assets/c0098f4e-6646-43e5-8c7b-b0616ee22b4e)


### Analysis with Pivot Tables:
- Generated insights into total profit, sales by coffee type and roast type, and profit by customer using Excel pivot tables.
- Used conditional formatting and line charts for visualizing trends in profit over time and identifying key metrics.
  ![Screenshot 2024-10-13 134651](https://github.com/user-attachments/assets/c6459c9b-69b0-4ff8-b0c5-794cbc274a61)


### Data Visualization:
- Applied conditional formatting to visualize profit by coffee type and roast.
- Created line charts to track profit trends over time for different coffee types.
- Generated a heat map to highlight profit variations across coffee categories and years.
  ![Screenshot 2024-10-13 134606](https://github.com/user-attachments/assets/07cb5526-889a-4912-9508-303f2bf9d12d)

![Screenshot 2024-10-13 134509](https://github.com/user-attachments/assets/b1888ad4-5935-4004-bbfd-126bc001eaf3)

