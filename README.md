
- Repository Overview:
  - This repository contains a database designed for a bike store, comprising three tables: brands, categories, and products.

- Dataset Description:
  - The dataset was crafted for exploratory data analysis and database management for the bike store.
  - It includes information about different bikes, brands, and categories.
  - Tables are linked through their ID columns, with the products table referencing categories and brands tables.

- Table Structures:
  - Products Table:
    - Unique identifiers for each bike (product_id).
    - Bike name (product_name).
    - Associated brand ID (brand_id).
    - Associated category ID (category_id).
    - Manufacturing year (model_year).
    - Price (list_price).
  - Categories Table:
    - Unique identifiers for each category (category_id).
    - Category names (category_name).
  - Brands Table:
    - Unique identifiers for each brand (brand_id).
    - Brand names (brand_name).

- SQL File Contents:
  - The SQL file contains various queries used for data exploration and manipulation:
    - Selecting specific columns from one or more tables.
    - Filtering data based on specific conditions.
    - Grouping and aggregating data based on certain columns.
    - Joining tables to combine data from multiple sources.

- Results and Insights:
  - Insights obtained from the data include:
    - Identification of brands with the most bikes in a specific category.
    - Determination of average bike prices within specific categories.
    - Identification of the most expensive bikes in specific categories.

- Future Work:
  - Future endeavors may involve:
    - Adding additional data to the tables.
    - Conducting further exploration to gain deeper insights.
    - Utilizing the database for larger applications or analytical projects for the bike store.

- Instructions for Use:
  - Ensure a SQL database management system is installed on your computer.
  - Create an empty database and import the provided SQL file.
  - Connect to the database using a SQL client and execute the queries as needed.
