# Demand Forecasting  
## AI-Driven Demand Prediction for Smarter Retail  

### **Description**  
This project leverages historical sales, impressions, and clicks data to build an AI-driven demand prediction model for smarter retail decision-making. By analyzing time-series patterns and external factors, the project aims to provide actionable insights to optimize inventory, marketing, and resource allocation strategies.

---

### **Features**  
1. **Data Preprocessing**:  
   - Merging datasets from multiple sources into a unified structure.  
   - Handling missing values and outliers using IQR-based techniques.  

2. **Exploratory Data Analysis (EDA)**:  
   - Visual insights using line graphs, scatter plots, and correlation heatmaps.  
   - Time-based trends via day-wise and month-wise data aggregations.  
   - Identification of seasonal and cyclical demand patterns.

3. **Time Series Modeling**:  
   - Comparison of ARIMA, SARIMA, ARIMAX, and SARIMAX models.  
   - Evaluated models based on metrics like MAE, RMSE, and MAPE to select the best approach for long-term forecasting.  
   - SARIMAX chosen for its ability to capture seasonality and align with real-world trends.

---

### **Results**  
- **Seasonality Insights**:  
  - Sales peak during weekends and in specific months (December and May).  
  - Clear seasonal trends identified using SARIMAX, improving long-term prediction reliability.  

- **Correlation Analysis**:  
  - Impressions and clicks strongly correlate with sales, emphasizing their importance as features in predictive modeling.  

- **Modeling Outcomes**:  
  - SARIMAX performed best in capturing seasonal trends and demand fluctuations despite slightly higher error metrics.  
  - ARIMAX maintained strong numerical performance, making it a reliable alternative baseline.

---

### **Conclusion**  
The project demonstrates how AI-driven forecasting models can enhance retail strategies by providing:  
- Accurate demand predictions, even for long-term periods.  
- Actionable insights into seasonal trends and key drivers of demand.  
- Improved decision-making for inventory management, marketing campaigns, and resource allocation.  

