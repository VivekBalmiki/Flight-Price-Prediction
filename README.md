# ✈️ Flight Price Prediction - Data-Driven Fare Estimation

This project focuses on analyzing flight prices using **Exploratory Data Analysis (EDA)** and **Feature Engineering** to build a predictive model. By leveraging machine learning techniques, the model aims to estimate flight ticket prices based on various factors.

## 🚀 Project Overview

- **Objective:** Develop a model to predict flight ticket prices based on historical data.
- **Tools & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn.
- **Dataset:** Contains flight details, including airline, departure time, duration, and ticket prices.

## 📂 Dataset Overview

- **flight_data.csv** – Includes airline details, departure & arrival times, total travel duration, number of stops, and ticket prices.

### 🔑 Key Features:
- **Flight Details:** Airline, Total Stops, Travel Duration.
- **Departure & Arrival Information:** Date, Time, Source, Destination.
- **Pricing:** Ticket prices as the target variable.

## 🛠️ Analysis & Preprocessing

### ✅ Data Cleaning & Preprocessing
- Handled missing values and formatted datetime features.
- Converted categorical features using encoding techniques.
- Applied **feature scaling** to normalize numerical data.

### ✅ Exploratory Data Analysis (EDA)
- Analyzed flight price trends based on airline, duration, and stopovers.
- Visualized price distribution using histograms and box plots.
- Identified correlations between features.

### ✅ Feature Engineering
- Created new features like **day of travel** and **duration categories**.
- Transformed existing variables to enhance predictive power.


## ▶️ How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/VivekBalmiki/Flight-Price-Prediction.git
   cd Flight-Price-Prediction
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas numpy seaborn matplotlib scikit jupyter
    ```
3.  **Open Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
4.  **Run the Notebook:** Open and execute the `Flight-Price-Prediction.ipynb` notebook.

## 📊 Next Steps - Model Training

 **Upcoming Tasks:**
- Train models such as Linear Regression, Decision Trees, and Random Forest.
- Evaluate models using metrics like RMSE and R² score.
- Fine-tune hyperparameters for better performance.
- Predict flight prices on test data.

## 🔜Future Enhancements
- Integrate real-time flight pricing APIs.
- Deploy the model as a web app using Flask or Streamlit.
- Optimize feature selection for improved accuracy.

## 🤝 Contributions & Feedback

Contributions are welcome! If you have suggestions or improvements, feel free to fork this repository and submit a pull request.

---

🚀 Let's predict flight prices with data! ✈️📊
