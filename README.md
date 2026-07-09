# Flight-Booking_Project
Developed a machine learning regression model to predict flight ticket prices based on historical booking data. Performed data preprocessing, feature engineering, exploratory data analysis. This project demonstrates an end-to-end ML workflow for predictive analytics in the travel industry

# ✈️ Flight Booking Price Prediction using Machine Learning

## 📌 Project Overview

Flight ticket prices fluctuate due to several factors such as airline, source, destination, journey date, departure time, arrival time, duration, and total stops. This project develops a **Machine Learning Regression model** to accurately predict flight ticket prices based on historical booking data.

The project includes data preprocessing, feature engineering, model training, evaluation, and hyperparameter tuning to identify the best-performing algorithm for price prediction.

---

## 🎯 Problem Statement

Predict the price of a flight ticket using historical flight booking data by applying regression-based machine learning algorithms. The objective is to build an accurate model that can assist travelers and booking platforms in estimating ticket prices before booking.

---

## 📂 Dataset

The dataset contains flight booking information with features such as:

* Airline
* Source
* Destination
* Date of Journey
* Departure Time
* Arrival Time
* Duration
* Total Stops
* Additional Information
* Ticket Price (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## ⚙️ Machine Learning Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Hyperparameter Tuning (GridSearchCV)
9. Model Comparison
10. Final Prediction

---

## 🤖 Models Implemented

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Tuned Decision Tree (GridSearchCV)

---

## 📊 Model Performance

| Model                   |     R² Score |
| ----------------------- | -----------: |
| Linear Regression       |   **0.9025** |
| Decision Tree Regressor |   **0.9832** |
| Random Forest Regressor | **0.9896** ⭐ |
| Tuned Decision Tree     |   **0.9870** |

### Evaluation Metrics

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

---

## 📈 Key Results

* Successfully built an end-to-end flight price prediction system.
* Compared multiple regression algorithms.
* Random Forest Regressor achieved the highest accuracy with an **R² Score of approximately 98.96%**.
* Improved Decision Tree performance using **GridSearchCV**.
* Visualized model performance through comparative charts.

---

## 🚀 Future Improvements

* Deploy the model using Flask or Streamlit.
* Integrate real-time flight booking APIs.
* Include additional features such as weather, holidays, and demand trends.
* Experiment with advanced boosting algorithms like XGBoost, LightGBM, and CatBoost.
* Build an interactive web application for users to predict flight prices.

---

## 📚 Learning Outcomes

This project helped me gain practical experience in:

* Data preprocessing and feature engineering
* Regression algorithms
* Model evaluation using R², MAE, and MSE
* Hyperparameter tuning with GridSearchCV
* Comparing machine learning models
* Data visualization
* Building an end-to-end machine learning pipeline

---

## 📌 Conclusion

This project demonstrates the application of supervised machine learning techniques to predict flight ticket prices accurately. After comparing multiple regression models, the **Random Forest Regressor** delivered the best performance with an **R² Score of 98.96%**, making it the most reliable model for this dataset. The project showcases a complete machine learning workflow—from data preprocessing to model optimization—and serves as a practical example of predictive analytics in the travel industry.

⭐ **If you found this project useful, feel free to star this repository and connect with me on LinkedIn!**
