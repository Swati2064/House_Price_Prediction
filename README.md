
# 🏠 USA House Price Prediction

A Machine Learning based web application for predicting house prices in the USA using multiple regression algorithms and Flask deployment.

---

# 📌 Project Overview

This project predicts house prices based on various housing features such as:

- Average Area Income
- Average Area House Age
- Average Area Number of Rooms
- Average Area Number of Bedrooms
- Area Population

The project trains multiple Machine Learning models, compares their performance, and allows users to make predictions through a Flask web application.

---

# 🚀 Technologies Used

- Python
- Flask
- Pandas
- Scikit-learn
- LightGBM
- XGBoost
- HTML
- CSS

---

# 📂 Project Structure

```bash
USA_House_price/
│
├── app.py
├── house_model.py
├── USA_Housing.csv
├── model_evaluation_results.csv
│
├── templates/
│   ├── index.html
│   ├── results.html
│   └── model.html
│
├── LinearRegression.pkl
├── RandomForest.pkl
├── XGBoost.pkl
├── LGBM.pkl
├── ...
│
└── README.md
````

---

# ⚙️ Machine Learning Models Used

The following models are trained and evaluated:

1. Linear Regression
2. Robust Regression
3. Ridge Regression
4. Lasso Regression
5. ElasticNet
6. Polynomial Regression
7. SGD Regressor
8. Artificial Neural Network (ANN)
9. Random Forest Regressor
10. Support Vector Machine (SVM)
11. LightGBM
12. XGBoost
13. K-Nearest Neighbors (KNN)

---

# 📊 Evaluation Metrics

The models are evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

Results are saved in:

```bash
model_evaluation_results.csv
```

---

# 🖥️ Flask Web Application

The Flask app allows users to:

✅ Select a Machine Learning model
✅ Enter house details
✅ Predict house prices
✅ View model evaluation results

---

# 📷 Application Screens

* Home Page
* Prediction Result Page
* Model Evaluation Page

---

# 📈 Future Improvements

* Add CSS styling
* Deploy on Heroku/Render
* Add user authentication
* Improve prediction accuracy
* Add graphical visualizations

---

# 👨‍💻 Author

Swati Jadhav


