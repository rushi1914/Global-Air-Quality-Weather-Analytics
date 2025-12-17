\# Global Air Quality \& Weather Analytics



\## Project Overview

This project presents an end-to-end analysis of global air quality and weather data.

The objective is to clean, unify, analyze, and model pollution patterns, with a primary

focus on \*\*PM2.5 concentration prediction\*\*.



The project demonstrates a complete data analytics pipeline, including:

\- Data profiling and cleaning

\- Exploratory Data Analysis (EDA)

\- Feature engineering

\- Regression and machine learning models

\- Time-series forecasting

\- Association rule mining (Apriori)



---



\## Dataset Description

The dataset contains air quality and weather measurements collected across multiple cities.



\*\*Key variables include:\*\*

\- Air pollutants: PM2.5, NO₂, O₃

\- Weather factors: temperature, humidity, wind speed

\- Temporal data: timestamp

\- Spatial data: latitude, longitude



All datasets are cleaned, validated, and standardized before analysis.



---



\## Project Structure



Global\_Air\_Quality\_Weather/

│

├── data/

│ ├── air\_quality\_clean.csv

│ ├── air\_quality\_transformed.csv

│ ├── aqi\_summary\_by\_city.csv

│ └── aqi\_category\_distribution.csv

│

├── notebooks/

│ └── Global-Air-Quality-Weather-Data-Unification.ipynb

│

├── outputs/

│ └── visualizations/

│ ├── data\_profiling\_cleaning/

│ ├── eda\_visualization/

│ ├── interactive\_visualization/

│ ├── regression\_models/

│ ├── advance\_ml\_models/

│ ├── time\_series\_forecasting/

│ └── association\_rule\_mining/

│

├── README.md

└── requirements.txt



---



\## Data Profiling \& Cleaning

Initial data quality checks were performed to identify missing values,

outliers, and distribution patterns before and after cleaning.



\_Click any image to view in full resolution.\_



\[!\[Missing Values Before Cleaning](outputs/visualizations/data\_profiling\_cleaning/01\_missing\_values\_before\_cleaning.png)](outputs/visualizations/data\_profiling\_cleaning/01\_missing\_values\_before\_cleaning.png)



\[!\[Distributions Before Cleaning](outputs/visualizations/data\_profiling\_cleaning/02\_distributions\_before\_cleaning.png)](outputs/visualizations/data\_profiling\_cleaning/02\_distributions\_before\_cleaning.png)



\[!\[Outliers Before Cleaning](outputs/visualizations/data\_profiling\_cleaning/03\_outliers\_boxplots\_before\_cleaning.png)](outputs/visualizations/data\_profiling\_cleaning/03\_outliers\_boxplots\_before\_cleaning.png)



\[!\[Post Cleaning Boxplots](outputs/visualizations/data\_profiling\_cleaning/04\_post\_cleaning\_boxplots.png)](outputs/visualizations/data\_profiling\_cleaning/04\_post\_cleaning\_boxplots.png)



---



\## Exploratory Data Analysis (EDA)

EDA focuses on pollution trends over time, city-wise comparisons,

and relationships between air quality and weather variables.



\[!\[PM2.5 Trends \& Top Polluted Cities](outputs/visualizations/eda\_visualization/08\_pm25\_trend\_over\_time\_and\_top\_polluted\_cities.png)](outputs/visualizations/eda\_visualization/08\_pm25\_trend\_over\_time\_and\_top\_polluted\_cities.png)



\[!\[Correlation Heatmap](outputs/visualizations/eda\_visualization/9\_correlation\_heatmap\_cleaned\_and\_engineered\_features.png)](outputs/visualizations/eda\_visualization/9\_correlation\_heatmap\_cleaned\_and\_engineered\_features.png)



---



\## Interactive Visualization

An interactive visualization was built to explore the relationship

between \*\*PM2.5 and temperature\*\* across different cities and AQI categories.



\[!\[Interactive PM2.5 vs Temperature](outputs/visualizations/interactive\_visualization/11\_interactive\_pm25\_vs\_temperature.png)](outputs/visualizations/interactive\_visualization/11\_interactive\_pm25\_vs\_temperature.png)



---



\## Regression Models

Multiple regression techniques were applied and compared to understand

linear and non-linear relationships.



\[!\[Simple Linear Regression](outputs/visualizations/regression\_models/12\_simple\_linear\_regression.png)](outputs/visualizations/regression\_models/12\_simple\_linear\_regression.png)



\[!\[Multiple Linear Regression](outputs/visualizations/regression\_models/13\_multiple\_linear\_regressio.png)](outputs/visualizations/regression\_models/13\_multiple\_linear\_regressio.png)



\[!\[Polynomial Regression](outputs/visualizations/regression\_models/14\_polynomial\_regression.png)](outputs/visualizations/regression\_models/14\_polynomial\_regression.png)



\[!\[Ridge \& Lasso Regression](outputs/visualizations/regression\_models/15\_ridge\_lasso\_regression.png)](outputs/visualizations/regression\_models/15\_ridge\_lasso\_regression.png)



---



\## Advanced Machine Learning Models

Tree-based ensemble models were implemented for improved prediction accuracy.



\[!\[Random Forest Results](outputs/visualizations/advance\_ml\_models/16\_random\_forest\_actual\_vs\_predicted.png)](outputs/visualizations/advance\_ml\_models/16\_random\_forest\_actual\_vs\_predicted.png)



\[!\[XGBoost \& LightGBM](outputs/visualizations/advance\_ml\_models/17\_xgboost\_lightgbm\_results.png)](outputs/visualizations/advance\_ml\_models/17\_xgboost\_lightgbm\_results.png)



\[!\[R² Score Comparison](outputs/visualizations/advance\_ml\_models/18\_r2\_score\_comparison\_table.png)](outputs/visualizations/advance\_ml\_models/18\_r2\_score\_comparison\_table.png)



---



\## Time Series Forecasting

Temporal models were used to forecast PM2.5 using lag features and time-based patterns.



\[!\[Time Series Prediction](outputs/visualizations/time\_series\_forecasting/19\_time\_series\_actual\_vs\_predicted.png)](outputs/visualizations/time\_series\_forecasting/19\_time\_series\_actual\_vs\_predicted.png)



\[!\[Residuals \& Feature Importance](outputs/visualizations/time\_series\_forecasting/20\_time\_series\_residuals\_and\_feature\_importance.png)](outputs/visualizations/time\_series\_forecasting/20\_time\_series\_residuals\_and\_feature\_importance.png)



---



\## Association Rule Mining (Apriori)

Apriori algorithm was applied to discover frequent pollution patterns

and relationships between environmental conditions.



\[!\[Frequent Itemsets](outputs/visualizations/association\_rule\_mining/21\_frequent\_itemsets.png)](outputs/visualizations/association\_rule\_mining/21\_frequent\_itemsets.png)



\[!\[Association Rules](outputs/visualizations/association\_rule\_mining/22\_association\_rules\_apriori.png)](outputs/visualizations/association\_rule\_mining/22\_association\_rules\_apriori.png)



---



\## Conclusion

This project showcases a complete real-world analytics workflow,

combining data cleaning, visualization, machine learning,

time-series forecasting, and pattern mining to extract

meaningful insights from air quality data.



---



\## Author

\*\*Rushikesh Kedar\*\*



