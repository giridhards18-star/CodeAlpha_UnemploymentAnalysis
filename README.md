# Unemployment Analysis with Python

## Data Science Internship Project

This project analyzes unemployment trends in India using Python.

## Objectives

- Clean and preprocess unemployment data
- Analyze overall unemployment trends
- Study the impact of COVID-19 on unemployment
- Compare unemployment across different regions
- Analyze monthly unemployment patterns
- Compare rural and urban unemployment
- Study correlations between numerical variables

## Dataset

The dataset contains information about:

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### 1. Overall Unemployment

The cleaned dataset contains 740 observations.

- Average unemployment rate: 11.79%
- Median unemployment rate: 8.35%
- Minimum unemployment rate: 0%
- Maximum unemployment rate: 76.74%

### 2. COVID-19 Impact

The analysis compares unemployment before and during the COVID-19 period.

- Before COVID average: 9.51%
- COVID period average: 17.77%
- Increase: 8.26 percentage points

### 3. Monthly Analysis

- Highest monthly average: April – 23.64%
- Lowest monthly average: July – 9.03%

### 4. Regional Analysis

The analysis compares unemployment rates across different regions.

Tripura recorded the highest average unemployment rate in the analyzed dataset at 28.35%.

### 5. Rural vs Urban Analysis

The project compares unemployment rates between rural and urban areas.

### 6. Correlation Analysis

A correlation heatmap was created to examine relationships between numerical variables such as unemployment rate, estimated employment, labour participation rate, year, and month.

## Project Structure

```text
Unemployement Analysis/
│
├── data/
├── notebooks/
├── visualization/
├── README.md
├── requirements.txt
└── .gitignore