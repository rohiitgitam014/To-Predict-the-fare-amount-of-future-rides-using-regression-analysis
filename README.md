Project Overview:
The project involves predicting future ride fare amounts based on historical ride data using regression techniques.

Dataset:
The dataset contains 200,000 rows with features such as fare_amount, pickup_datetime, pickup_longitude, pickup_latitude, dropoff_longitude, dropoff_latitude, and passenger_count.
After removing null values, the dataset was cleaned and prepared for analysis.
Data Preprocessing:
Unnecessary columns like Unnamed: 0 were dropped, and any missing values were handled.
Visualizations were created to analyze the relationship between features such as pickup_datetime, fare_amount, and passenger_count.
Correlation Analysis:
A correlation matrix was generated, indicating weak correlations between most features and fare_amount. For example, the correlations with pickup_longitude and dropoff_longitude were minimal.
Model Development:
Data Splitting: The data was divided into training (70%) and testing (30%) sets.
PCA (Principal Component Analysis): Dimensionality reduction was applied to simplify the feature set.
Modeling: A RandomForestRegressor was used to predict the fare amount.
Model Evaluation:
The model performed well, achieving an R² score of 94% on the training set and 93% on the test set.
