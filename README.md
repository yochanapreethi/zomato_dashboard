# Zomato Restaurant Insights Dashboard

## Overview

This Power BI dashboard analyzes Zomato restaurant data to reveal trends in customer behavior, cuisine preferences, cost distributions, and city-level performance. The dashboard is designed to support data-driven decisions in the food services sector through interactive and insightful visualizations.

## File Contents

| File/Folder               | Description                                                                                          |
|---------------------------|------------------------------------------------------------------------------------------------------|
| `zomato_dashboard.pbix`   | Power BI dashboard file with full interactivity                                                      |
| `zomato_dashboard.pdf`    | Exported version of the full dashboard in PDF format                                                 |
| `data/`                   | Folder containing the dataset (`menu.csv`, `users.csv`, `orders.csv`)                                |
| `assets/`                 | Custom icons and UI assets used in the report design                                                 |
| `README.md`               | Documentation and usage instructions                                                                 |

## Key Features

- **Ratings Analysis**  
  Visualize how restaurants are rated across different cities and cuisine types

- **Cuisine Trends**  
  Discover the most common and highly rated cuisines

- **City-Wise Insights**  
  Explore restaurant density, performance, and distribution across cities

- **Cost Evaluation**  
  Analyze cost for two and its correlation with customer satisfaction

- **Service Type Breakdown**  
  Examine patterns in delivery, dine-in, or hybrid restaurant models

- **Interactive Filtering**  
  Use slicers to dynamically explore the dataset by city, cost, rating, service type, and cuisine

## Tools & Technologies

- **Power BI Desktop** – For dashboard creation and interaction  
- **Power Query** – Used for data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – Custom calculations and metrics  
- **Visual Assets** – Custom backgrounds and icons from the `assets/` folder

## Getting Started

1. **Install Power BI Desktop**  
   Download from [https://powerbi.microsoft.com/desktop](https://powerbi.microsoft.com/desktop)

2. **Open the Report**  
   - Open `zomato_dashboard.pbix` in Power BI Desktop to interact with the full report  
   - Alternatively, view `zomato_dashboard.pdf` for a static summary

3. **Explore the Data**  
   - Navigate to `data/data.csv` to review the source dataset  
   - Key columns include:  
     `Restaurant Name`, `City`, `Cuisine`, `Rating`, `Cost for Two`, `Online Delivery`, `Table Booking`

## Use Cases

- Monitor food and dining trends across different cities  
- Identify high-performing cuisines and service models  
- Guide strategic planning for marketing, pricing, and expansion  
- Support restaurant decision-making with data-backed insights

> For feedback, improvements, or collaboration, feel free to contribute or raise an issue.
