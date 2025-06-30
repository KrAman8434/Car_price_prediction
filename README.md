# 🚗 Car Price Prediction

A machine learning project that predicts car prices based on various features like brand, model, year, fuel type, transmission, and more. This project follows the end-to-end ML pipeline including data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

---

## 📌 Problem Statement

The objective of this project is to predict the **resale price of a car** using supervised machine learning techniques. Accurate price prediction helps car dealerships and customers make informed decisions.

---

## 📂 Dataset

- **Source**: `cars.csv` (custom or public dataset)
- **Features Include**:
  - Brand
  - Registration_Year
  - Selling Price (Target)
  - Present Price
  - Fuel Type
  - Mileage
  - Engine V

---

## 🔧 Tools & Technologies Used

- **Language**: Python
- **Libraries**:
  - pandas, numpy, matplotlib, seaborn
  - scikit-learn (Linear Regression)
- **Environment**: Jupyter Notebook

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for nulls and data types
- Visualized distributions and boxplots
- Analyzed relationships between features and target variable
- Detected outliers and skewed data

---

## 🧹 Data Preprocessing

- Converted categorical features using Label Encoding / OneHotEncoding
- Created derived features (e.g., "Car Age" from manufacturing year)
- Split dataset into training and test sets

---

## 🧠 Models Used

| Model             | R² Score | Remarks                    |
|------------------|----------|----------------------------|
| Linear Regression | ✅ Basic baseline model            |


Evaluation Metrics:
- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (optional)

---

## 📈 Results

- **Best Model**: Random Forest Regressor
- Achieved high R² and low error on test set
- Importance of features like Present Price, Car Age, and Fuel Type was highlighted

---

## 📌 Key Learnings

- Hands-on understanding of preprocessing real-world structured data
- Implemented and compared multiple regression models
- Gained insights into feature importance and model evaluation techniques

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Use advanced models like XGBoost or LightGBM
- Deploy the model using Flask or Streamlit
- Add interactive dashboard using Power BI or Plotly Dash

---

## 📁 How to Run

```bash
1. Clone this repo
2. Install required packages: pip install -r requirements.txt
3. Open `Car Price Prediction.ipynb` in Jupyter Notebook
4. Run all cells to see results
