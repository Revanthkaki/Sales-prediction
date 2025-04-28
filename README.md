# Sales-prediction
Forecast product sales based on historical data to help businesses optimize their marketing and sales strategies.

🎯 Project Objective
Predict car purchase amounts using customer demographic and financial information.

Analyze the impact of factors like age, salary, credit card debt, and net worth.

Handle missing data, detect outliers, apply scaling techniques for better model performance.

Evaluate models using MAE, RMSE, and R² Score.

Visualize important relationships and model performance to draw actionable insights.

📊 Approach
1. Data Preprocessing
Dropped irrelevant features (customer name, email).

Encoded categorical variables (Country, Gender).

Scaled numerical features using StandardScaler.

2. Exploratory Data Analysis (EDA)
Correlation heatmaps to study feature relationships.

Boxplots to detect and visualize outliers.

3. Model Building
Linear Regression for baseline.

Random Forest Regressor for ensemble-based predictions.

XGBoost Regressor for boosting-based powerful predictions.

4. Model Evaluation
Compared models using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

XGBoost showed the best performance with highest R² score.

5. Visualizations
Correlation between features.

Feature importance (Random Forest).

Actual vs Predicted plots.

🏆 Results

Model	MAE	RMSE	R² Score
Linear Regression	~2.1	~3.2	~0.95
Random Forest	~1.5	~2.1	~0.98
XGBoost	~1.4	~2.0	~0.98
✅ XGBoost outperformed other models with the highest R² score, making it the preferred choice for forecasting.

📈 Key Visuals

Visualization	Description
Correlation Heatmap	Shows relationships between variables
Boxplots	Detect and visualize outliers
Feature Importance	Highlights most influential features
Actual vs Predicted	Checks model accuracy visually
