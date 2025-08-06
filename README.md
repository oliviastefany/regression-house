# regression-house
🏡 House Price Prediction using Linear Regression
This project focuses on predicting house prices using a Linear Regression model. The workflow involves data preparation, feature evaluation, model training, and performance assessment using RMSE and R² metrics

📁 Dataset
The dataset used in this project is publicly available on Kaggle: https://www.kaggle.com/datasets/prokshitha/home-value-insights

⚙️ Project Workflow
- Import libraries for data handling, visualization, and modeling
- Check for missing values
- Visualize key variables to explore patterns and correlations
- Split data into training and testing sets
- Train a linear regression model
- Interpret coefficients
- Make predictions and evaluate performance

🔍 Key Observations
- Square footage shows a clear linear correlation with house price — larger homes tend to cost more
- Year built has no visible relationship with price — data points are randomly scattered
- Lot size, garage size, and neighborhood quality appear to have minimal impact on price in this dataset
- The data is normally distributed, so no log transformation was needed

📈 Model Evaluation
- R² Score: 0.97 — the model explains 97% of the variance in house prices
- RMSE: only 5.6% of the average house price — indicating low prediction error
- Overall, the model demonstrates strong and reliable performance
