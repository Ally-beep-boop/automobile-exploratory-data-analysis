# Automobile Dataset | Exploratory Data Analysis

An exploratory data analysis (EDA) project using Python to investigate relationships between automobile pricing, fuel efficiency, engine specifications, and vehicle manufacturers.

The project focuses on cleaning and preparing raw data, identifying patterns, and presenting findings through data visualisations.

## Project Overview

The objective of this project was to explore an automobile dataset and understand how different vehicle characteristics relate to pricing, performance, and fuel economy.

The analysis explores several questions:

- Which vehicles are the most and least expensive?
- Do more expensive vehicles offer better fuel efficiency?
- Which manufacturers produce the most fuel-efficient vehicles?
- Which vehicles have the largest engines?
- Which manufacturers are most represented in the dataset?
- Is there a relationship between engine size and vehicle price?

## Technologies Used

- Python – Data analysis and processing
- Pandas – Data manipulation, cleaning, and aggregation
- NumPy – Numerical data handling
- Matplotlib – Data visualisation
- Seaborn – Statistical data visualisation
- Jupyter Notebook – Analysis, documentation, and presentation

## Dataset

The automobile dataset contains 205 vehicle records and 26 original features, including:

- Vehicle manufacturer and body style
- Fuel type and drive configuration
- Engine size and horsepower
- City and highway fuel economy
- Vehicle price

The dataset required preprocessing before analysis, including handling missing values and correcting data types.

## Data Cleaning and Preprocessing

The following preprocessing steps were performed:

1. Identified and removed columns not required for the analysis.
2. Checked for duplicate records.
3. Converted missing-value placeholders (?) into recognised null values.
4. Removed records containing missing data.
5. Converted numerical columns into appropriate data types.
6. Prepared the cleaned dataset for further analysis.
7. After cleaning, the dataset contained 193 records and 24 columns.

## Exploratory Data Analysis

The analysis included several visualisations and comparisons:

- Vehicle Pricing: Identified the five most expensive and five cheapest vehicles.
- Price vs Fuel Efficiency: Compared average highway MPG between expensive and affordable vehicles.
- Manufacturer Fuel Efficiency: Analysed average highway MPG across manufacturers.
- Engine Capacity: Identified vehicles with the largest engines.
- Manufacturer Representation: Compared the number of vehicles represented by each manufacturer.
- Engine Size vs Price: Investigated the relationship between engine capacity and vehicle pricing.

Key Findings

1. Higher prices do not necessarily indicate better fuel efficiency.

The five cheapest vehicles generally achieved higher average highway MPG than the five most expensive vehicles.

2. Fuel efficiency varies across manufacturers.

Chevrolet, Honda, and Volkswagen were among the manufacturers with the highest average highway MPG in the dataset.

3. Engine size is associated with vehicle price.

The analysis revealed a positive relationship between engine size and price, with larger engines generally appearing in more expensive vehicles.

4. Toyota had the highest representation in the dataset.

Toyota accounted for the largest number of vehicle records, followed by several other major manufacturers.

5. Vehicle value depends on different priorities.

The results highlight trade-offs between affordability, fuel economy, engine capacity, and premium vehicle positioning.

## How to Run the Project

1. Clone or download this repository.

2. Ensure Python 3 and Jupyter Notebook are installed.

3. Install the required libraries:

pip install pandas numpy matplotlib seaborn jupyter

4. Place the dataset file (automobile.txt) in the project directory.

5. Open the Jupyter Notebook.

6. Run the cells in sequence to reproduce the analysis and visualisations.

## Project Report

A detailed PDF report is included in this repository, containing the preprocessing steps, Python code, visualisations, findings, and final conclusions.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Data manipulation with Pandas
- Data visualisation
- Descriptive statistical analysis
- Identifying trends and relationships
- Analytical thinking and interpretation
- Communicating findings through reports

## Future Improvements

Potential improvements include:

- Investigating missing-value imputation instead of removing incomplete records.
- Performing correlation analysis to quantify relationships between numerical variables.
- Exploring additional factors influencing automobile prices.
- Building a regression model to predict vehicle prices.
- Creating an interactive dashboard to explore the findings.

## Author

Ally Remas
