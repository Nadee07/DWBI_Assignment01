This project covered the full BI pipeline - from data extraction to analytical reporting - using industry-standard tools and concepts.

Key highlights of the project:


 🔹 Dataset Selection - brazilian e-commerce dataset (Kaggle) covering 2 years of retail transactions including customers, products, orders, and sales data.
 🔹 Multi-Source Integration - Integrated data from 3 heterogeneous sources: SQL Server database, CSV files, and TXT files.
 🔹 Data Warehouse Design - Designed a Star Schema with FactSales and 4 dimension tables (Dim_Customer, Dim_Product, Dim_Seller, Dim_Date) with well-defined  hierarchies.
 🔹 SCD Type 2 Implementation - Implemented Slowly Changing Dimension logic in Dim_Customer to preserve historical changes in customer attributes.
 🔹 ETL with SSIS - Developed SSIS packages for staging, transformation, and loading processes with surrogate key resolution using Lookup transformations.
 🔹 Accumulating Fact Table - Extended FactSales to track the order lifecycle and processing time from creation to completion.

This project strengthened my understanding of the complete data warehousing lifecycle - from source system integration to dimensional modeling and ETL implementation -highlighting how structured data architecture enables effective business intelligence and decision-making.
