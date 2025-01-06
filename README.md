# India_kii_Hava

All steps lisited below,

Data Collection
The dataset was sourced from Kaggle, containing air quality metrics for multiple cities in India, including AQI and pollutant concentrations (PM10, PM2.5, NO2, etc.).
Which you can find here- https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india

Data Preprocessing
Handling Missing Values: Removed or imputed missing values where necessary to ensure data completeness.
Datetime Conversion: Converted the Date column into a datetime format for temporal analysis.
Categorization: Grouped data by regions, cities, and seasons (Summer, Winter, Monsoon) for meaningful comparisons.

Exploratory Data Analysis (EDA)
EDA was conducted to address key questions:
Regional and Temporal Trends: Analyzed AQI variations across different regions using line plots and heatmaps.
Frequency of Severe AQI: Identified cities experiencing frequent severe or poor AQI using bar charts.
Pollutant Correlations: Used correlation matrices to explore relationships between AQI and pollutants like PM2.5 and PM10.
Seasonal Patterns: Examined seasonal spikes and improvements.

Data Visualization
Python libraries Matplotlib and Seaborn were used for data visualization to highlight trends and patterns.

Tools and Libraries
Python: pandas, matplotlib, seaborn
Jupyter Notebook for code execution and visualization.
