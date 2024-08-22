<div align="center">
  <img src="https://github.com/user-attachments/assets/b6769283-308d-41d9-849c-46ff70cdab77" width=350, height=300>
</div>

# Predictive Analysis of the Consumer Price Index in Malaysia Using ARIMA and LSTM Models

**Skills:**

---
**Situation:** </br>
In Malaysia, monitoring and forecasting the Consumer Price Journey (CPI), a critical measure of inflation, is essential for economic planning and policy-making. The project utilizes CPI data from 1980 to 2005, a period of significant economic transformation, to build predictive models. Given the complexity of the CPI data, which includes variables like food, housing, and transport, an effective forecasting model could greatly aid in economic decision-making and planning.

**Task:** </br>
Data Preparation and Analysis: Responsible for preparing the Consumer Price Index (CPI) dataset for Malaysia (1980-2005) to build a reliable forecasting model. This involved ensuring data integrity, selecting relevant features, and analyzing the data to understand trends and seasonal patterns.

**Action:** 
* Data Preparation: Loaded the dataset into a Pandas DataFrame, handled missing values, and ensured no duplicates were present. Updated column names for clarity, converted numerical columns to appropriate data types, and transformed the 'Year' column into a datetime format.
* Feature Selection: Applied feature selection to focus on the most relevant data, retaining only essential columns like 'Year' and 'Total' for a more interpretable forecasting model.
* Seasonal Decomposition: Performed seasonal decomposition to identify and separate trend, seasonal, and residual components, aiding in understanding the underlying patterns in the CPI data.
* ARIMA Model Development: Conducted grid search for optimal ARIMA parameters, split data into training and testing sets, and defined and fitted the ARIMA model using the best order identified.
* LSTM Model Development: Normalized the data, created sequences for the LSTM input, constructed the LSTM model with appropriate architecture, and trained it using the Adam optimizer and MSE loss function.

**Results:** </br>
As illustrated in Figure 1, the LSTM model demonstrated superior performance in forecasting Malaysia's CPI compared to the ARIMA model. This effectiveness highlights the LSTM's capability in handling complex datasets, suggesting a promising application for deep learning in economic forecasting.
</br>

<div align="center">
  <figure>
    <img src="https://github.com/user-attachments/assets/026e2571-bf10-4479-8642-537dad0933f5" width=350, height=300></br>
    <figcaption>Figure 1: Model Performance Comparison</figcaption>
</div></br>

This substantial difference in RMSE values not only proves the higher accuracy of the LSTM model but also indicates its potential to significantly enhance economic policy-making with more precise forecasts.








