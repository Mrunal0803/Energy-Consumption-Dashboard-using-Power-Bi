# Energy-Consumption-Dashboard-using-Power-Bi
⚡ Energy Consumption Dashboard | Power BI






📌 Overview

This project presents an interactive Energy Consumption Dashboard built using Power BI to analyze Water, Electricity, and Gas usage across multiple buildings and cities.

The dashboard enables stakeholders to monitor consumption, track costs, identify trends, and optimize energy usage through data-driven insights. 

Report on Energy Consumption Da…

🧠 Problem Statement

Energy suppliers often struggle with:

Disconnected energy data

Limited visibility into consumption patterns

Rising operational costs

Lack of centralized reporting

This dashboard solves these challenges by providing a single, unified analytical view of energy consumption and costs. 

Report on Energy Consumption Da…

🛠 Tech Stack

Power BI Desktop

Power Query (ETL)

DAX

Data Modeling

Exploratory Data Analysis (EDA)

📂 Dataset

The project uses three structured tables:

Table Name	Description
Building Master	Building, City, Country (11 buildings)
Energy Consumptions	Date, Building, Energy Type, Units, Year (2016–2019)
Rates	Year-wise energy price per unit

✔️ Data was clean with no inconsistencies detected. 

Report on Energy Consumption Da…

🔄 Data Preparation

Cleaned and transformed data using Power Query

Created a unique ID (Year + Energy Type) to link consumption and rates

Optimized tables for efficient modeling

🔗 Data Modeling

Building Master → Energy Consumptions (Building)

Energy Consumptions → Rates (Custom ID)

This structure ensures accurate calculations and performance efficiency. 

Report on Energy Consumption Da…

📐 Key DAX Measures

Total Energy Cost

Total Units Consumed

Cost by Energy Type

Units by Energy Type

% Contribution by Energy Type

Remaining Units by Energy Type

📊 Dashboard Pages
🔹 Overview

Total Buildings

Total Energy Cost

Total Units Consumed

Energy Type Breakdown

💧 Water Consumption

City & Building-wise usage

Year-wise cost and trend

⚡ Electricity Consumption

Consumption by City & Building

Cost trend analysis

🔥 Gas Consumption

Gas usage comparison

Year-wise consumption & cost

📈 Key Insights

Water contributes ~88.5% of total energy usage, yet cost remains stable

Gas consumption and cost decline consistently from 2016–2019

New York shows the highest water and gas usage

Los Angeles incurs the highest electricity cost

Strong potential for cost optimization through water conservation

Report on Energy Consumption Da…

🎯 Business Value

Centralized energy monitoring

Improved cost visibility

Trend and anomaly detection

Supports strategic energy planning

🚀 How to Run

Download the .pbix file

Open in Power BI Desktop

Refresh data

Use slicers to explore insights by Year, City, Building, Energy Type

👤 Author

📊 Data Analyst

⭐ If you find this useful

Give the repo a ⭐ and feel free to fork or improve it!
