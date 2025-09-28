# EV Data Visualisation Dashboard

## Overview
An **interactive Tableau dashboard** for exploring the adoption of **electric vehicles (EVs)** across **time, geography, and vehicle models**.  
The project demonstrates **dimensional modelling**, **data integration**, and **business intelligence** techniques, combining multiple datasets into a single structured view.  
The dashboard provides an **intuitive interface** to explore the data in various ways - filtering, drilling down, and switching between perspectives without needing to write queries.

## Key Features
- **Interactive dashboard** with filters and drill-downs.  
- **Geographic analysis** of EV adoption across regions.  
- **Temporal trends** showing year-on-year growth.  
- **Manufacturer and model segmentation** for side-by-side comparison.  
- Powered by a **fact-dimension schema** for reliable reporting.  

## Tech Stack
- **Tableau Desktop** – dashboard design and visualisation.  
- **Excel** – dataset preparation and dimensional modelling.  

## Dataset Structure
The project follows a **star schema**, a common data warehouse design where a central **fact table** is linked to several **dimension tables**.  
This structure supports fast, intuitive analysis by separating numeric measures (facts) from descriptive attributes (dimensions).  

- `FactEVPopulation.xlsx` – EV population counts (fact table).  
- `DimGeography.xlsx` – regional attributes.  
- `DimModel.xlsx` – manufacturer and model details.  
- `DimYear.xlsx` – temporal attributes.  

## How It Works
The Tableau workbook (`Dashboard.twb`) connects the fact and dimension tables to form the star schema.  
This design enables analysis across **time, geography, and vehicle models**.  
Calculated fields, filters, and parameters allow users to drill down and explore adoption patterns dynamically.

## Usage
1. Clone or download the repository.  
2. Open `Dashboard.twb` in **Tableau Desktop** *(tested on 2023.2)*.  
3. Ensure the Excel files are in the same folder as the workbook.  
4. Use filters and visuals to explore EV adoption trends.  

## Results
The dashboard makes the data accessible by providing an **interactive, intuitive way** to:  
- Track **growth in EV adoption** over time.  
- Compare **manufacturers and models** directly.  
- Identify **regional differences** in uptake.  

*(Note: Tableau software is required to view the dashboard.)*  

## Learning Outcomes
- Designed and implemented a **star schema** for BI reporting.  
- Built an **interactive dashboard** in Tableau from scratch.  
- Integrated and prepared **multi-source datasets** for analysis.  

## Future Work
- Automate dataset refreshes with **live connections**.  
- Add **forecasting models** for predicting future EV adoption.  
- Expand scope with **charging infrastructure** and **policy impact data**.  
