# Car Price Prediction using Machine Learning

A machine learning project built with Python and Scikit-learn to predict the selling prices of used cars based on various features like present price, driven kilometers, fuel type, and transmission.

## 🚀 Project Overview
Accurately predicting used car prices helps buyers and sellers understand market value. This project uses a **Linear Regression** model trained on historical car data to forecast selling prices.

## 🛠️ Tools & Technologies Used
* **Python**
* **Pandas** (for data manipulation and cleaning)
* **Scikit-learn** (for building and evaluating the machine learning model)
* **Google Colab** (as the development environment)

## 📊 Model Performance
* **Algorithm:** Linear Regression
* **Evaluation Metric:** R² Score
* **Result:** Achieved an **$R^2$ Score of 0.85**, meaning the model explains 85% of the variance in car prices.

## 📂 Dataset Features
The dataset includes the following parameters:
* `Car_Name`: Name of the car model
* `Year`: Manufacturing year
* `Present_Price`: Current ex-showroom price (in lakhs)
* `Driven_kms`: Total distance driven by the car in kilometers
* `Fuel_Type`: Petrol, Diesel, or CNG
* `Selling_type`: Dealer or Individual
* `Transmission`: Manual or Automatic
* `Owner`: Number of previous owners
* **Target Variable:** `Selling_Price` (Price at which the car is sold)

## 💻 How to Run
1. Clone this repository or download the files.
2. Open the `Car_Price_Prediction.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Upload your `car data.csv` file when prompted.
4. Run the cells step by step to train the model and view the evaluation metrics.
