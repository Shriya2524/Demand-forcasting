# **Demand Forecasting**  
## **AI-Driven Demand Prediction for Smarter Retail**  

### **Project Description**  
This project leverages historical sales, impressions, and clicks data to build an AI-driven demand prediction model. By integrating time-series analysis and multivariate regression, it aims to provide actionable insights that optimize inventory, marketing, and resource allocation strategies for smarter retail decision-making.

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
     - Evaluated models using metrics such as MAE, RMSE, and MAPE to select the best-fit approach for long-term forecasting.  
     - **SARIMAX** was chosen for its superior ability to capture seasonal patterns and align with real-world trends.  
   - **Multivariate Regression**:  
     - Dynamic regression incorporating lagged variables to capture dependencies across predictors.  
     - Comparison with basic multiple regression models.  
     - Evaluated performance using Adjusted R-squared, RMSE, and MAE metrics.  

---

### **Results**  
- **Seasonality Insights**:  
  - Sales peak during weekends and specific months (December and May).  
  - Seasonal trends identified using **SARIMAX**, enhancing long-term prediction reliability.  

- **Correlation Analysis**:  
  - Impressions and clicks strongly correlate with sales, emphasizing their importance as predictive features.  

- **Performance Comparison**:  
  - While **SARIMAX** captured seasonal trends and demand fluctuations better than other models, the **Multivariate Regression** model demonstrated better performance in short-term and dynamic forecasting scenarios.  
  - **SARIMAX** was selected as the final model for its superior ability to reflect seasonal and cyclical trends crucial for long-term decision-making.  

---

### **Conclusion**  
This project showcases how AI-driven forecasting models, complemented by multivariate regression, can enhance retail strategies through:  
- Accurate predictions for both short-term and long-term horizons.  
- Actionable insights into seasonal trends, lagged dependencies, and demand drivers.  
- Optimized decision-making for inventory management, marketing campaigns, and resource allocation.  

By integrating **time-series analysis** and **multivariate regression**, the project highlights the synergy between historical patterns and dynamic predictor relationships, enabling smarter and more informed retail decision-making.

