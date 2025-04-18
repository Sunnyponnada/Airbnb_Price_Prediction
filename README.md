# 🏠Airbnb Price Prediction Project and Insights

**Objective:** Predict Airbnb listing prices using various property features.

**Model:** XGBoost model

**Includes:** Data Cleaning, Preprocessing, Visualizations, Model Building & Evaluation

 ### Overview
 Airbnb provides a platform for property owners to rent out their spaces to travelers. Pricing a
 listing effectively is critical for maximizing revenue while staying competitive in the market.
 For hosts, understanding what factors influence the price of their listings is essential.
 This project aims to build a machine learning model to predict the price of Airbnb listings
 based on various features such as property type, room type, location, amenities, and host
 characteristics. By analyzing these factors, this project will provide actionable insights to
 Airbnb hosts to optimize their listing prices

 ### Problem Statement
 The primary objective of this project is to develop a regression model that predicts the price
 of an Airbnb listing. Using features such as property type, room type, number of reviews,
 location, and amenities, the model will aim to estimate the price accurately.
 The insights derived from this analysis will help Airbnb hosts understand the key drivers of
 price, enabling them to make data-driven decisions for pricing their properties. Additionally,
 the project will help Airbnb refine its recommendations for pricing to improve host and guest
 satisfaction

 ### Packages used
 Pandas
 NumPy
 Matplotlib
 Seaborn
 Sciket learning
 XGboost 

 **Done few types of regression task such as *linear regression*, *Random forest*, *lasso regression*, and *XGBoost* **
 XGBoost model performed much better in predicting the prices.
 Top Features ![download](https://github.com/user-attachments/assets/3c05620f-63ef-413f-a21f-68aff3d74671)

 XGBoost Results:
 RMSE : 0.44
MAE  : 0.33
R2 Score : 0.62

 Linear Regression: RMSE=256613081.083, MAE=3899024.902, R²=-128675962797942592.000
Ridge Regression:  RMSE=0.411, MAE=0.298, R²=0.669
Lasso Regression:  RMSE=0.441, MAE=0.323, R²=0.620

Random Forest Results:
RMSE: 0.4574176671845301
MAE: 0.340767687554969
R^2 Score: 0.5927187575411195

## 📌 Key Insights & Summary
- **Room Type, Property Type, and Location significantly influence prices.**
- **More amenities = Higher price.**
- **Verified hosts and instant bookable listings tend to be priced higher.**
- **Model Performance:** Linear Regression & Ridge performed well. Choose Linear Regression for interpretability.

