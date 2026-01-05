Bengaluru House Price Prediction Machine Learning Regression Model
📖 Overview

This project aims to predict house prices in Bengaluru using machine learning techniques. The dataset comprises various features like area type, availability, location, size, and total square footage. By analyzing these attributes, a model is developed to learn pricing patterns and make predictions.

⚙️ Tech Stack

Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Algorithm: Linear Regression

🧠 Approach

Data Loading & Initial Exploration: Loaded the dataset and performed initial checks on its structure, missing values, and unique entries.

Data Cleaning: Handled missing values in 'location', 'total_sqft_numeric', and 'area_type_encoded'. Cleaned and transformed 'area_type', 'availability', 'size', and 'total_sqft' columns into suitable numerical formats.

EDA (Exploratory Data Analysis): Visualized the distribution of property prices and their relationships with key features such as total square footage, area type, and availability.

Feature Engineering: Converted the 'location' categorical feature into numerical format using one-hot encoding.

Model Building: Trained a Linear Regression model using the prepared features.

Evaluation: Assessed the model's performance on a test dataset.

📊 Results

R-squared (R2): 0.4156
Mean Absolute Error (MAE): 43.68
Root Mean Squared Error (RMSE): 116.74
These metrics indicate a moderate fit for the Linear Regression model, explaining approximately 41.6% of the variance in house prices.

📁 Dataset

Bengaluru House Data (from a local CSV file, likely /content/drive/MyDrive/Bengaluru_House_Data.csv)

👨‍💻 Author

[Your Name/Alias Here] | Aspiring ML Engineer | Data Science Enthusiast
