# Sales Data Pipeline Using Azure Data Factory

# Project Overview

This project demonstrates how to build a simple data pipeline using Azure Data Factory (ADF). The pipeline moves raw sales data from Azure Blob Storage to an Azure SQL Database and performs basic data transformations using ADF's Data Flow feature. The pipeline includes operations such as filtering invalid data and aggregating total sales per product.


# Technologies Used

Azure Data Factory for data integration and pipeline orchestration.

Azure Blob Storage to store the raw sales data CSV file.

Azure SQL Database to store the transformed sales data.

Data Flow in ADF for data cleaning and transformation.


# Dataset
The raw sales data is stored in a CSV file with the following structure:

SaleID: Unique identifier for each sale.

Date: Date of the sale.

ProductID: ID of the product sold.

Quantity: Number of units sold.

TotalPrice: Total price of the sale.

# Future Improvements

Add more complex transformations .
