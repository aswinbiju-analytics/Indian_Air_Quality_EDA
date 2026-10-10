# Indian Air Quality Exploratory Data Analysis

## Project Overview

This project explores air quality data from India using Python. It examines the Air Quality Index (AQI), AQI categories, state-wise and city-wise averages, seasonal patterns, and pollutant measurements.

The goal is to understand patterns in the available air quality data through data analysis and visualization.

## Dataset Overview

- Total records: 10,521
- Cities covered: 268
- States covered: 30
- Minimum recorded AQI: 0
- Maximum recorded AQI: 499

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. Imported and inspected the dataset.
2. Examined missing values and duplicate records.
3. Converted date information into datetime format.
4. Created date-based features for analysis.
5. Analysed AQI distributions and categories.
6. Compared average AQI across states and cities.
7. Explored seasonal AQI patterns.
8. Examined pollutant measurements and numerical correlations.
9. Created and saved visualizations.
10. Summarized the findings and limitations.

## Key Findings

- The dataset contains 10,521 records from 268 cities across 30 states.
- The overall average AQI is 118.24.
- The median AQI is 89.
- The most frequently occurring AQI category is Good.
- Sikkim has the highest average AQI in this dataset, at 149.66.
- Cuddalore has the highest average AQI in this dataset, at 197.0.

These findings describe this dataset and should not be interpreted as definitive rankings of air quality across India.

## Visualizations

The `Visualizations/` folder contains charts covering:

- AQI distribution
- AQI category distribution
- Top 10 states by average AQI
- Top 10 cities by average AQI
- AQI categories across seasons
- Average pollutant measurements
- Numerical correlation heatmap
- Average AQI by season
- Top 10 cities by record count

## Project Structure

```text
Indian_Air_Quatity_EDA/
├── Data/
│   └── raw/
│       └── enriched_aqi_dataset.csv
├── notebooks/
│   └── Indian_Air_Quality_EDA.ipynb
├── Visualizations/
├── README.md
├── requirements.txt
└── .gitignore
```

## Conclusion

This project demonstrates how Python can be used to inspect, analyse, and visualize environmental data. It provided practical experience in data exploration, missing-value analysis, feature engineering, aggregation, statistical summaries, and data visualization.

## Limitations

The findings depend on the available data, observation periods, and monitoring coverage. The analysis identifies patterns but does not establish the causes of air pollution.