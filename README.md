# Coffee Sales Dashboard in Excel

![obraz](https://github.com/user-attachments/assets/5475ccef-8392-4749-b145-859db0d9daa3)


## Overview
This project involves creating an interactive **Coffee Sales Dashboard** in Excel using slicers for dynamic filtering. The dataset consists of three tables: **Orders, Customers, and Products**. The dashboard provides insights into sales performance, customer trends, and product popularity.

## Features
- **Data Processing**:
  - Used **XLOOKUP** and **INDEX & MATCH** to populate the Orders table with relevant customer and product details.
- **Dashboard Elements**:
  - Interactive slicers for filtering by date, and product.
  - Sales trend analysis using charts.

## Data Structure
- **Orders Table**: Contains transaction details (Order ID, Date, Customer ID, Product ID, Quantity, and Revenue).
- **Customers Table**: Stores customer information (Customer ID, Name, Country, and Loyalty Card).
- **Products Table**: Includes product details (Product ID, Coffee Type, Roast Size, and Price).

## How It Works
1. Data is pulled from the **Customers** and **Products** tables using **XLOOKUP** and **INDEX & MATCH**.
2. The **Orders** table is updated dynamically based on these lookups.
3. The dashboard visualizes key metrics using pivot tables and slicers.
4. Users can interact with the slicers to filter data dynamically and analyze specific aspects of sales performance.





