# Demand Forecasting  
## AI-Driven Demand Prediction for Smarter Retail  

### **Description**  
This project leverages historical sales, impressions, and clicks data to build an AI-driven demand prediction model for smarter retail decision-making. By analyzing time-series patterns and incorporating multivariate regression analysis, the project aims to provide actionable insights to optimize inventory, marketing, and resource allocation strategies.

---

### **Features**  
1. **Data Preprocessing**:  
   - Merging datasets from multiple sources into a unified structure.  
   - Handling missing values and outliers using IQR-based techniques.  
   - Creating lagged variables for predictors like sales, clicks, and impressions for dynamic regression modeling.  

2. **Exploratory Data Analysis (EDA)**:  
   - Visual insights using line graphs, scatter plots, and correlation heatmaps.  
   - Time-based trends via day-wise and month-wise data aggregations.  
   - Identification of seasonal and cyclical demand patterns.

3. **Modeling Techniques**:  
   - **Time Series Modeling**:  
     - Comparison of ARIMA, SARIMA, ARIMAX, and SARIMAX models.  
     - Evaluated models based on metrics like MAE, RMSE, and MAPE to select the best approach for long-term forecasting.  
     - SARIMAX chosen for its ability to capture seasonality and align with real-world trends.  
   - **Multivariate Regression**:  
     - Dynamic regression incorporating lagged variables to capture dependencies across predictors.  
     - Comparison of dynamic regression with basic multiple regression models.  
     - Evaluated performance using Adjusted R-squared, RMSE, and MAE metrics.

---

### **Results**  
- **Seasonality Insights**:  
  - Sales peak during weekends and in specific months (December and May).  
  - Clear seasonal trends identified using SARIMAX, improving long-term prediction reliability.  

- **Correlation Analysis**:  
  - Impressions and clicks strongly correlate with sales, emphasizing their importance as features in predictive modeling.  

- **Modeling Outcomes**:  
  - **SARIMAX**: Performed best in capturing seasonal trends and demand fluctuations, despite slightly higher error metrics.  
  - **Multivariate Regression**: Showed improved flexibility by incorporating multiple predictors and lagged variables, leading to better short-term and dynamic predictions.  
  - **Dynamic Regression Models**: Outperformed basic regression models with superior Adjusted R-squared and reduced RMSE, showcasing the advantage of accounting for temporal relationships between variables.

---

### **Conclusion**  
The project demonstrates how AI-driven forecasting models, complemented by multivariate regression, can enhance retail strategies by providing:  
- Accurate demand predictions for both short-term and long-term horizons.  
- Actionable insights into seasonal trends, lagged dependencies, and key drivers of demand.  
- Improved decision-making for inventory management, marketing campaigns, and resource allocation.  

This dual modeling approach (time series and multivariate regression) highlights the synergy between historical patterns and dynamic relationships among predictors for smarter retail decision-making.  

