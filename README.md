# Weather Data Analysis

## Project Overview  
This project analyzes weather data to identify patterns and relationships between meteorological factors such as temperature, humidity, wind speed, pressure, visibility, and precipitation. Additionally, the study builds machine learning models to predict the daily weather summary based on historical weather data.  

### Objectives  
1. Exploratory Data Analysis to identify trends and correlations between weather attributes.  
2. Outlier Detection and Data Cleaning to process raw data and remove anomalies.  
3. Weather Prediction Modeling to classify weather summaries such as clear, foggy, and overcast.  
4. Hypothesis Testing to validate if temperature and humidity are positively correlated.  

## Dataset  
- Description: Contains multiple years of weather observations.  
- Attributes:  

| Feature | Description |
|---------|-------------|
| Formatted Date | Date and time of the weather observation |
| Temperature | Actual temperature recorded |
| Apparent Temperature | Feels-like temperature |
| Humidity | Humidity levels on a scale of zero to one |
| Wind Speed | Speed of the wind in kilometers per hour |
| Wind Bearing | Wind direction in degrees |
| Visibility | Distance visible at the time in kilometers |
| Pressure | Atmospheric pressure in millibars |
| Precipitation Type | Type of precipitation such as rain or snow |
| Daily Summary | Short description of the day's weather |

## Exploratory Data Analysis  

### Data Cleaning and Outlier Removal  
Techniques Used:  
- Handled missing values by removing or imputing them.  
- Detected outliers using box plots and statistical methods.  
- Converted categorical features such as Daily Summary into numerical labels.  

Data Reduction Results:  
- Initial records contained a large dataset with thousands of entries.  
- After cleaning and outlier removal, inconsistencies were significantly reduced.  

### Key Trends and Correlations  
Findings from Visualizations:  
- Temperature and humidity showed a strong positive correlation where higher temperature leads to increased humidity.  
- Temperature and wind speed showed a negative correlation where wind speed tends to decrease on hotter days.  
- Visibility and cloud cover showed an inverse relationship where clearer days had higher visibility.  
- Pressure trends over time showed seasonal fluctuations.  

Visualizations Used:  
- Box plots for outliers  
- Line charts for trends over time  
- Heatmaps for correlation analysis  
- Bar graphs for categorical distributions  

## Machine Learning Models  

### Model Selection and Evaluation  
Four machine learning models were trained and compared to find the best model for predicting the daily weather summary.  

| Model | Accuracy Percentage | Precision Percentage | Best Use Case |
|--------|--------------------|--------------------|------------------|
| Logistic Regression | 79.5 | 79.3 | Basic linear classification |
| K Nearest Neighbors | 83.7 | 83.7 | Non linear classification |
| Decision Tree | 89.7 | 89.6 | Rule based decision making |
| Random Forest | 94.1 | 94.1 | Best performance and robust |

Random Forest was the best performing model with an accuracy of 94.1 percent.  

## Technologies and Tools  

| Technology | Purpose |
|------------|---------|
| Python | Data Cleaning, Analysis, Machine Learning |
| Jupyter Notebook | Interactive Data Exploration |
| Pandas | Data Preprocessing and Manipulation |
| Matplotlib and Seaborn | Data Visualization |
| Scikit Learn | Machine Learning Model Training |
| TensorFlow | Deep Learning Experiments |
| NumPy | Numerical Computation |
| DateTime | Handling Time Series Data |

## Key Findings  

### Temperature and Humidity Correlation  
Confirmed Hypothesis that higher temperature is associated with increased humidity.  

### Weather Summaries and Attributes  
Overcast and foggy days had higher humidity and lower visibility.  
Clear days had higher temperature and lower humidity.  

### Best Model for Weather Prediction  
Random Forest achieved 94.1 percent accuracy, making it the most reliable model for daily weather summary prediction.  

## Future Scope  

- Improve model performance by using deep learning models for time series forecasting.  
- Expand dataset to incorporate real time weather data for improved accuracy.  
- Develop a system for weather anomaly detection to identify extreme weather events.  
