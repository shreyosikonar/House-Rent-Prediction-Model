# 🏠 House Rent Prediction Model

A Machine Learning project that predicts house rental prices using **Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn**. The project includes data analysis, visualization, preprocessing, and regression-based prediction.

## 📌 Project Overview

Finding an appropriate rental price for a property can be difficult because rent depends on several factors such as property characteristics, location, size, and other features.

This project applies **Machine Learning and Multiple Linear Regression** to analyze housing data and predict rental/property prices based on available features.

The project was developed using **Jupyter Notebook** and Python's data science and machine learning libraries.

## 🎯 Objectives

* Analyze housing/property data.
* Perform data cleaning and preprocessing.
* Explore relationships between different features and property prices.
* Visualize important patterns in the dataset.
* Build a Machine Learning regression model.
* Predict property prices using the trained model.
* Evaluate the performance of the prediction model.

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization
* **Scikit-learn** – Machine Learning
* **HTML/CSS** – Application interface

## 📂 Project Structure

```text
House-Rent-Prediction-Model/
│
├── boston.csv
├── boston_app.ipynb
├── multiple linear regression.ipynb
│
├── model_predict/
│   └── Model prediction files
│
├── templates/
│   └── Application templates
│
└── README.md
```

## 📊 Dataset

The project uses a housing dataset containing property-related information used for price prediction.

The dataset is stored in:

```text
boston.csv
```

The data is loaded and analyzed using **Pandas** before being used for model training.

## 🔍 Exploratory Data Analysis

The project performs Exploratory Data Analysis (EDA) to understand the dataset and identify relationships between different variables.

The analysis includes:

* Understanding the dataset structure
* Checking data types
* Checking missing values
* Statistical analysis
* Feature relationships
* Correlation analysis
* Data visualization
* Identifying patterns and trends

## 📈 Data Visualization

Different visualization techniques are used to understand the relationship between the features and the target variable.

The project uses:

* Scatter plots
* Distribution plots
* Correlation heatmaps
* Regression plots
* Other exploratory visualizations

These visualizations help identify which features have a stronger relationship with property prices.

## 🤖 Machine Learning Model

The project uses **Multiple Linear Regression** for prediction.

### Multiple Linear Regression

Multiple Linear Regression is a supervised Machine Learning algorithm used to predict a continuous target variable using multiple independent variables.

The general form of the model is:

```text
Y = b0 + b1X1 + b2X2 + ... + bnXn
```

Where:

* `Y` = Predicted property price
* `X1, X2, ... Xn` = Input features
* `b0` = Intercept
* `b1, b2, ... bn` = Model coefficients

## 🔄 Machine Learning Workflow

The project follows the following workflow:

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Price Prediction
```

## 📚 Project Files

### `multiple linear regression.ipynb`

This notebook contains the main Machine Learning workflow, including:

* Data loading
* Data exploration
* Data preprocessing
* Visualization
* Model building
* Model training
* Prediction
* Evaluation

### `boston_app.ipynb`

This notebook contains the application-related implementation for using the trained prediction model.

### `model_predict/`

Contains files related to model prediction/application functionality.

### `templates/`

Contains the templates used by the application interface.

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/shreyosikonar/House-Rent-Prediction-Model.git
```

### 2. Navigate to the project directory

```bash
cd House-Rent-Prediction-Model
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open:

```text
multiple linear regression.ipynb
```

Run the cells sequentially to reproduce the analysis and prediction process.

## 📌 Key Learning Outcomes

Through this project, I gained practical experience in:

* Python programming
* Data cleaning and preprocessing
* Exploratory Data Analysis
* Data visualization
* Feature analysis
* Supervised Machine Learning
* Multiple Linear Regression
* Model training and prediction
* Working with Jupyter Notebook
* Organizing and managing a Machine Learning project using GitHub

## 🔮 Future Improvements

The project can be further improved by:

* Comparing multiple regression algorithms.
* Performing advanced feature engineering.
* Applying hyperparameter tuning.
* Improving model accuracy.
* Adding additional real-world housing features.
* Building a more interactive user interface.
* Deploying the prediction application online.
* Adding model performance visualizations.
* Using larger and more recent housing datasets.

## 👩‍💻 Author

**Shreyosi Konar**

GitHub:
https://github.com/shreyosikonar

LinkedIn:
https://www.linkedin.com/in/shreyosi-konar-ab7012293/

---

⭐ If you found this project useful, feel free to explore the repository and provide feedback.
