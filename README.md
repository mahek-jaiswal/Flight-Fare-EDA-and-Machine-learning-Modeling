✈️ Flight Fare Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting flight ticket prices using Machine Learning techniques. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, and building predictive models.

The goal is to understand how different factors like airline, journey date, duration, and stops affect flight prices and to build a model that can accurately predict fares.

📂 Project Structure
├── Flight-Fare-EDA.ipynb        # Data Analysis & Visualization
├── Flight-Fare-ML-MODEL.ipynb   # Model Building & Evaluation
├── README.md                    # Project Documentation
📊 Dataset Features

The dataset contains information about flight bookings:

Airline
Date of Journey
Source
Destination
Route
Dep_Time (Departure Time)
Arrival_Time
Duration
Total_Stops
Additional_Info
Price (Target Variable)
🔍 Exploratory Data Analysis (EDA)

In the EDA notebook, the following steps are performed:

Handling missing values
Converting date & time into useful features
Extracting:
Journey Day & Month
Departure Hour & Minute
Duration in hours/minutes
Visualizations:
Price vs Airline
Price vs Stops
Price vs Duration
Identifying trends and outliers
⚙️ Data Preprocessing
Removed irrelevant columns (e.g., Route, Additional_Info)
Converted categorical data using:
One-Hot Encoding
Label Encoding
Feature scaling (if applied)
Splitting data into training and testing sets
🤖 Machine Learning Models Used

The following models are implemented:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
📈 Model Evaluation

Models are evaluated using:

R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)

Random Forest generally performs best due to handling non-linear relationships effectively.

🚀 How to Run the Project
1. Clone Repository
git clone https://github.com/your-username/flight-fare-prediction.git
cd flight-fare-prediction
2. Install Dependencies
pip install numpy pandas matplotlib seaborn scikit-learn
3. Run Notebooks

Open Jupyter Notebook:

jupyter notebook

Run:

Flight-Fare-EDA.ipynb
Flight-Fare-ML-MODEL.ipynb
📌 Key Insights
Ticket prices vary significantly by airline
More stops generally reduce ticket cost
Duration and departure time impact price
Certain routes are more expensive
🧠 Future Improvements
Hyperparameter tuning (GridSearchCV)
Use advanced models (XGBoost, Gradient Boosting)
Deploy model using Flask/Django
Create a user interface for predictions
🏷️ Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
🙌 Acknowledgment

This project is part of a Machine Learning learning journey and demonstrates practical implementation of regression techniques.# Flight-Fare-EDA-and-Machine-learning-Modeling
