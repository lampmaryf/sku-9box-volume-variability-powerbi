# SKU 9-Box Volume & Variability Analysis (Power BI)
This project implements a **SKU-level 9-box segmentation** using forecasted volume and demand variability to support demand planning and inventory strategy decision.

## Overview
The analysis segments SKUs based on:
- **12-month forecast volume**
- **Demand variability (Coefficient of Variaction, COV)**

Each SKU is classified into a 9-box framework (A1-C3) to help identify:
- High-volume, stable SKUs that require tight service levels
- Low-volume, high-variability SKUs with higher planning risk
- Opportunities to differentiate inventory and forecasting strategies

 ## Approach
 - Source data provided in Excel format
 - Data transformed and modeled using **Power Query**
 - **DAX measures** used to calculate forecast volume, demand variability, and SKU classifications
 - A Power BI scatter plot visualizes the 9-box framework with custom threshold lines

## Key Features
- SKU-level volume and variability classification
- Interactive 9-box scatter visualization
- Clear indentification of planning risk segments
- Designed for demand planning and supply chain decision-making

## Tools Used
- Power BI
- DAX
- Power Query
- Excel (source data)

## Screenshots 
![SKU 9-Box Scatter](screenshot/sku_9box_scatter.png)
![SKU Classification Table](screenshot/sku_9box_table.png)
