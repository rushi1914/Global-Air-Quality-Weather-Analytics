\# Global Air Quality \& Weather Data Analysis



\## Project Overview

This project performs end-to-end analysis of global air quality and weather data.  

The goal is to clean and unify the dataset, analyze pollution patterns, and build predictive models for PM2.5 levels.



The workflow covers:

\- Data profiling and cleaning  

\- Exploratory data analysis (EDA)  

\- Feature engineering  

\- Predictive modeling  

\- Time-series forecasting  

\- Association rule mining  



---



\## Dataset

The dataset contains air quality and weather measurements from multiple cities, including:

\- PM2.5, NO₂, O₃

\- Temperature, humidity, wind speed

\- Timestamp and geographic coordinates



All data is cleaned, validated, and standardized before analysis.



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

│

├── README.md

└── requirements.txt



---



\## Data Profiling \& Cleaning



Missing values, distributions, and outliers were analyzed before and after cleaning.



!\[Missing Values Before Cleaning](outputs/visualizations/data\_profiling\_cleaning/01\_missing\_values\_before\_cleaning.png)



!\[Distributions Before Cleaning](outputs/visualizations/data\_profiling\_cleaning/02\_distributions\_before\_cleaning.png)



!\[Outliers Before Cleaning](outputs/visualizations/data\_profiling\_cleaning/03\_outliers\_boxplots\_before\_cleaning.png)



!\[Post Cleaning Boxplots](outputs/visualizations/data\_profiling\_cleaning/04\_post\_cleaning\_boxplots.png)



---



\## Exploratory Data Analysis (EDA)



Trends, correlations, and city-wise pollution analysis.



!\[PM2.5 Trend and Top Cities](outputs/visualizations/eda\_visualization/08\_pm25\_trend\_over\_time\_and\_top\_polluted\_cities.png)



!\[Correlation Heatmap](outputs/visualizations/eda\_visualization/9\_correlation\_heatmap\_cleaned\_and\_engineered\_features.png)



---



\## Interactive Visualization



Dynamic PM2.5 vs Temperature visualization.



!\[Interactive Plot](outputs/visualizations/interactive\_visualization/11\_interactive\_pm25\_vs\_temperature.png)



---



\## Regression Models



Comparison of multiple regression techniques.



!\[Simple Linear Regression](outputs/visualizations/regression\_models/12\_simple\_linear\_regression.png)



!\[Multiple Linear Regression](outputs/visualizations/regression\_models/13\_multiple\_linear\_regressio.png)



!\[Polynomial Regression](outputs/visualizations/regression\_models/14\_polynomial\_regression.png)



!\[Ridge \& Lasso Regression](outputs/visualizations/regression\_models/15\_ridge\_lasso\_regression.png)



---



\## Advanced Machine Learning Models



Performance comparison of tree-based models.



!\[Random Forest](outputs/visualizations/advance\_ml\_models/16\_random\_forest\_actual\_vs\_predicted.png)



!\[XGBoost \& LightGBM](outputs/visualizations/advance\_ml\_models/17\_xgboost\_lightgbm\_results.png)



!\[R² Comparison](outputs/visualizations/advance\_ml\_models/18\_r2\_score\_comparison\_table.png)



---



\## Time Series Forecasting



PM2.5 forecasting using lag features and temporal modeling.



!\[Time Series Prediction](outputs/visualizations/time\_series\_forecasting/19\_time\_series\_actual\_vs\_predicted.png)



!\[Residuals \& Feature Importance](outputs/visualizations/time\_series\_forecasting/20\_time\_series\_residuals\_and\_feature\_importance.png)



---



\## Association Rule Mining (Apriori)



Identifying pollution-related patterns.



!\[Frequent Itemsets](outputs/visualizations/association\_rule\_mining/21\_frequent\_itemsets.png)



!\[Association Rules](outputs/visualizations/association\_rule\_mining/22\_association\_rules\_apriori.png)



---



\## Conclusion



This project demonstrates a complete real-world data analytics pipeline,

from raw data to actionable insights, using statistical analysis,

machine learning, and time-series forecasting techniques.



## Author

Rushikesh

