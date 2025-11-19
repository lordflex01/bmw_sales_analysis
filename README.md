# bmw_sales_analysis
BMW Global Sales Analysis (2010–2024)

## Overview

This project analyzes global BMW sales data from 2010 to 2024, with a specific focus on the transition from combustion engines to electric mobility.
Using a dataset containing various attributes (model, year, fuel type, region, mileage, price, etc.), the project explores key trends in sales, pricing, and energy types.

## Objectives

- Analyze total sales by energy type (Petrol, Diesel, Hybrid, Electric).
- Study the evolution of electric vs. thermal sales over time.
- Compare regional sales patterns.
- Evaluate average prices of electric models.
- Examine the “High/Low” Sales_Classification.

## Dataset Description

The dataset contains the following fields:

Column	Description
Model	BMW model name
Year	Year of sale
Region	Geographic region
Color	Vehicle color
Fuel_Type	Petrol / Diesel / Electric / Hybrid
Transmission	Manual / Automatic
Engine_Size_L	Engine size (liters)
Mileage_KM	Average mileage
Price_USD	Selling price
Sales_Volume	Number of units sold
Sales_Classification	High / Low classification

## Disclaimer — Data Limitations

This dataset contains intentional inconsistencies, as required by the assignment. They do not represent real BMW sales figures.

### Detected inconsistencies

- Electric and hybrid sales appear before 2013, despite BMW not offering electric models until then.
- Some models have unrealistic energy types (e.g., i8 Diesel).
- Sales volumes are unrealistically high for certain models (e.g., 20M+ units for the 7 Series).

### How they were handled

- For analyses involving market share or long-term comparisons, electric and hybrid data before 2013 were excluded to avoid bias.
- All original rows were preserved to respect the dataset's educational purpose.
- Interpretations focus on relative trends, not absolute values.

*These data are synthetic and should not be compared to real BMW statistics.*

## Methodology

- Data cleaning: missing values, duplicates, inconsistencies
- Exploratory analysis
- Visualization with Matplotlib (sales trends, regional breakdowns, price analysis)
- Interpretation in the context of the energy transition

## Visualizations

### Key charts produced include:

- Evolution of electric vs. thermal sales (2010–2024)
- Market share by energy type
- Average price of electric models
- Regional sales distribution
- Hybrid growth as a transitional technology

## Key Insights

- Electric vehicles gain significant market share over the period.
- Thermal engines remain dominant early on but decrease over time.
- Hybrid models play an important role as a transition phase.
- Strong regional disparities reflect different adoption rates.

## Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- PowerBI

## Installation
```
git clone https://github.com/lordflex01/bmw_sales_analysis.git
cd bmw_sales_analysis
pip install -r requirements.txt
```

## Run the Notebook
```
jupyter notebook projet_python.ipynb
```

## Author
Project created as part of a data analysis assignment.
