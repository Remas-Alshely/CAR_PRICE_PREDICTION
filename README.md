# 🚗 Car Price Prediction

A Machine Learning project that predicts the estimated price of a car based on its specifications and features. This project demonstrates the end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and price prediction.

---

## 📌 Project Overview

The objective of this project is to build a regression model that predicts the selling price of a used car based on various attributes such as mileage, fuel type, horsepower, manufacturing year, transmission type, and other relevant features.

---

## 📊 Dataset Features

The dataset includes the following features:

- Brand / Make
- Model
- Manufacturing Year
- Mileage
- Horsepower (HP)
- Fuel Type
- Transmission Type
- Offer Type
- Selling Price (Target Variable)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Car_Price_Prediction.git
```

Move into the project directory:

```bash
cd Car_Price_Prediction
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## 🚀 Usage

1. Open the Jupyter Notebook.

```bash
jupyter notebook
```

2. Run all the notebook cells.

3. Train the machine learning model.

4. Predict car prices using new input data.

Example:

```python
sample_car = {
    "Mileage": 120000,
    "Make": "BMW",
    "Model": "316",
    "Fuel": "Diesel",
    "Gear": "Manual",
    "OfferType": "Used",
    "HP": 126,
    "Year": 2011
}

predicted_price = model.predict(sample_car)
print(predicted_price)
```

---

## 🤖 Machine Learning Workflow

- Data Collection
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Splitting
- Model Training
- Model Evaluation
- Price Prediction

---

## 📈 Model Evaluation

The model is evaluated using standard regression metrics such as:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## ✨ Key Features

- Predicts used car prices using machine learning
- Performs data preprocessing and feature engineering
- Implements a regression model for prediction
- Includes model evaluation using multiple metrics
- Easy-to-understand Jupyter Notebook implementation

---

## 👨‍💻 Author

**Remas**
