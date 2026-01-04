# House-Price-Prediction-Using-Machine-Learning
## Task Objective
To predict house prices in King County, Washington using various property features (size, location, amenities, etc.) through regression modeling.

## Dataset Used
King County House Sales Dataset (kc_house_data.csv) with 21,613 entries and 21 features including price, bedrooms, bathrooms, square footage (living, lot, basement), year built, zipcode, grade, condition, and location coordinates.

## Models Applied
Linear Regression (from sklearn.linear_model), with data preprocessing including outlier removal (Z-score), feature scaling (MinMaxScaler to [1,8] range), and train-test split (80/20).

Key Results and Findings

R² Score: 0.736 (testing), explaining ~74% of price variance

Errors: MAE = $103,905, RMSE = $183,427

Strong predictors: Square footage (living space) showed highest correlation with price

Data quality: Required cleaning for ambiguous values (0 bedrooms) and outliers

Limitations: Linear model may miss non-linear relationships; error margins indicate room for improvement

