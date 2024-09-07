# Real-Estate-Price-Analysis-with-Snowflake
This project focuses on analyzing real estate prices using data sourced from Otodom. The data, initially provided in CSV format, has been processed and analyzed using Snowflake and Snowsight.

## Architectural Diagram
![diagram-export-9-7-2024-9_34_00-PM](https://github.com/user-attachments/assets/45098cec-fb44-49fa-9f96-2944697e0897)

## Steps involved

<h3>Data Loading:</h3>

Data Source: The dataset was obtained from Otodom and is in CSV format.
Snowflake Setup: Created a Snowflake database and warehouse.
Staging: Loaded the CSV data into a Snowflake stage using Snowflake's staging capabilities.
Data Import: Imported the data from the stage table into the main table using the COPY INTO command.

<h3>Data Processing:</h3>

Data Management: Performed necessary Data Definition Language (DDL) and Data Manipulation Language (DML) operations to clean, transform, and structure the data.
Data Enhancement: Implemented various data cleaning and enhancement techniques to make the dataset more meaningful and ready for analysis.

<h3>Data Analysis:</h3>

Dashboard Creation: Developed a comprehensive data analytics dashboard using Snowsight, Snowflake’s modern web UI for interactive data visualization.
Analysis Focus: The dashboard provides insights into real estate price trends, market dynamics, and property features, offering valuable information for understanding pricing patterns and market conditions.

<h3>Tools and Technologies:</h3>

Snowsight Modern Web UI: Utilized for data warehousing, staging, loading, creating and visualizing the data analytics dashboard.
