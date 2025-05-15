# NYC-Taxi-Fare-Prediction-A-Regression-Analysis-Project
NYC Taxi Fare Prediction: A Regression Analysis Project
This project showcases an end-to-end data science workflow, focusing on predicting taxi fare amounts in New York City. Commissioned by the NYC Taxi and Limousine Commission (NYC TLC) and undertaken as a data analytics consultant for Automatidata, the primary goal was to build a robust multiple linear regression model.

## Project Highlights:
### Objective: 
To develop a predictive model for NYC taxi fares using a dataset collected over a year.
### Methodology: 
The core of this project is the application of multiple linear regression, a technique used to estimate the linear relationship between a continuous dependent variable (fare amount) and two or more independent variables.
### Process:
* #### Exploratory Data Analysis (EDA):
  Thorough EDA was conducted to understand data distributions, identify outliers, handle missing values, and check for multicollinearity. This crucial step involved visualizing data and making informed decisions 
  about data cleaning and preprocessing.
* #### Feature Engineering:
  New features were created to enhance model performance, such as calculating trip `duration` from pickup and dropoff times, and deriving `mean_distance` and `mean_duration` for specific pickup/dropoff location 
  pairs. 
  Temporal features like `day` of the `week`, `month`, and a binary rush_hour indicator were also engineered.
* #### Model Building & Evaluation:
  Following EDA and feature engineering, the data was split into training and testing sets. A multiple linear regression model was built and rigorously evaluated using metrics suchs as R-squared, Mean Absolute 
  Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) on both training and test data to assess its performance and generalizability.

### Key Considerations: 
The project involved careful handling of outliers in variables like `fare_amount` and `duration` using imputation techniques based on interquartile range (IQR). It also addressed specific data characteristics, such as flat fares for airport trips (e.g., JFK to Manhattan), which were identified and appropriately handled.
