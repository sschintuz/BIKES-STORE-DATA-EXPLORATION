Seoul Bike Sharing Demand Prediction

Problem Description:

Rental bikes are introduced in urban cities to enhance mobility comfort, necessitating stable supply prediction for public accessibility. Predicting bike counts per hour is crucial for ensuring availability and reducing waiting time.

Data Description:

The dataset includes weather data (Temperature, Humidity, Windspeed, etc.) and hourly bike rental counts along with date information.

Attribute Information:
- Date: Year-month-day
- Rented Bike Count: Count of bikes rented per hour
- Hour: Hour of the day
- Temperature: Temperature in Celsius
- Humidity: Percentage
- Windspeed: m/s
- Visibility: 10m
- Solar Radiation: MJ/m2
- Rainfall: mm
- Snowfall: cm
- Seasons: Winter, Spring, Summer, Autumn
- Holiday: Holiday/No holiday
- Functional Day: NoFunc (Non-Functional Hours), Fun (Functional hours)

Preprocessing:
- Checked for null values and removed duplicates.
- Converted "date" column into separate columns for year, month, and day.
- Changed int64 columns into category columns.
- Removed correlated features like Dew point temperature.
- Handled outliers and filled null values with mean values.
- Conducted exploratory data analysis (EDA) on categorical and numerical variables.

Modeling:
- Used various regression models like Linear Regression, Ridge Regression, Elastic Net, Random Forest Regressor, XGBoost Regressor.
- Tuned hyperparameters using GridSearchCV for Random Forest and XGBoost models.
- Evaluated models based on metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.

Conclusion:
- Hour of the day, season, and weather conditions significantly influence bike rentals.
- Extreme Gradient Boosting (XGBoost) and Random Forest Regressor with hyperparameter tuning performed best, providing the lowest RMSE and highest R-squared scores.
- Project aims at predicting bike demand, aiding in bike sharing service optimization for urban mobility.
