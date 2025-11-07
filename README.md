🌱 Sustainability – Air Quality Index (AQI) Prediction

This project focuses on promoting environmental sustainability by predicting the Air Quality Index (AQI) using real-world pollution data.
It uses key air pollutants such as PM2.5, PM10, NO₂, SO₂, O₃, and CO to determine the air quality category and provide actionable insights for public health awareness.

🧠 Project Workflow

Data Collection & Cleaning

Collected and prepared the air quality dataset (city_day.csv) from Kaggle.

Handled missing values and filtered essential pollutant features.

Exploratory Data Analysis (EDA)

Visualized data trends and relationships using heatmaps and statistical plots.

Identified key pollutants most correlated with AQI.

Model Development

Implemented and compared models:

Linear Regression (Baseline)

Random Forest Regressor (Advanced)

Tuned hyperparameters and improved accuracy using feature importance analysis.

Model Evaluation & Saving

Evaluated using Mean Squared Error (MSE) and R² Score.

Saved trained models as aqi_prediction_model.pkl and aqi_prediction_model_v2.pkl for reuse.

Prediction

Model predicts AQI for given pollution levels and classifies air quality (e.g., Good, Moderate, Poor).

📊 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Google Colab

🏁 Results

Linear Regression Model: R² = 0.90

Random Forest Model (Improved): R² = 0.94

Demonstrated better predictive power and interpretability with pollutant-level feature importance.

💾 Files Included
File Name	Description
sustainability_air_quality.ipynb	Main Colab notebook with data cleaning, visualization, and model training code
city_day.csv	Air quality dataset used for training
aqi_prediction_model.pkl	Baseline trained model (Linear Regression)
aqi_prediction_model_v2.pkl	Advanced trained model (Random Forest)
README.md	Project summary and documentation
