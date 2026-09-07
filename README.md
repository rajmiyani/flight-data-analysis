# ✈️ Flight Data Analysis

A Python-based data analytics and machine learning project that explores a flight dataset to understand flight delays, travel distance, air time, and carrier performance.

The project covers **data understanding, exploratory data analysis (EDA), data preprocessing, statistical analysis, data visualization, regression, classification, and model evaluation** using Python.

---

## 📌 Project Overview

This project analyzes flight data to identify patterns and relationships between different flight-related variables.

The analysis focuses mainly on:

* Departure delays
* Arrival delays
* Flight distance
* Air time
* Airline carriers
* Relationships between flight variables
* Factors associated with flight delays

The project also applies machine learning models to predict arrival delays and classify whether a flight is delayed.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand the structure and characteristics of the flight dataset
* Perform exploratory data analysis
* Analyze distributions and relationships between variables
* Identify and handle missing values
* Detect and understand the impact of outliers
* Calculate statistical measures
* Automate common EDA operations using reusable Python functions
* Perform regression analysis
* Build supervised machine learning models
* Classify flights as delayed or on-time
* Evaluate model performance
* Visualize important findings from the dataset

---

## 🛠️ Technologies & Libraries

The project is developed using Python and the following libraries:

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computing
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning and model evaluation
* **Jupyter Notebook** – Development and analysis environment

---

## 📊 Analysis Performed

### 1. Data Understanding

The dataset is loaded using Pandas and analyzed to understand:

* First and last records
* Dataset shape
* Column names
* Quantitative variables
* Qualitative variables
* Discrete and continuous variables

---

### 2. Exploratory Data Analysis

#### Univariate Analysis

The following variables are analyzed:

* `dep_delay`
* `arr_delay`
* `distance`

Visualizations include:

* Histograms
* Boxplots

#### Bivariate Analysis

Relationships between variables are explored using scatter plots:

* Distance vs Air Time
* Departure Delay vs Arrival Delay
* Distance vs Arrival Delay

#### Multivariate Analysis

Multivariate relationships are explored using:

* Pair plots
* Correlation matrix
* Heatmap

---

### 3. Missing Data & Outlier Handling

Missing values are identified and handled using median-based imputation for selected numerical variables.

Outliers are analyzed using boxplots, with particular attention to extreme flight delays and their potential impact on statistical analysis and predictive models.

---

### 4. Statistical Analysis

The project calculates:

* Mean
* Median
* Standard Deviation
* Skewness
* Kurtosis

These statistics are used to understand the distribution and spread of the flight data.

---

### 5. Automated EDA

A reusable Python function is created to automate common exploratory data analysis operations, including:

* Dataset information
* Descriptive statistics
* Correlation analysis
* Missing-value counts

---

## 🤖 Machine Learning

### Linear Regression

The project applies:

* Simple Linear Regression
* Multiple Linear Regression

**Target variable:**

`arr_delay` — Arrival Delay

**Independent variables:**

* `dep_delay` — Departure Delay
* `distance` — Flight Distance

---

### Logistic Regression

A classification target is created:

* `1` → Flight delayed
* `0` → Flight on-time

The classification model uses:

* Departure delay
* Distance
* Air time

to classify whether a flight is delayed.

---

## 📈 Model Evaluation

Regression models are evaluated using:

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* R² Score

The classification model is evaluated using:

* Accuracy Score
* Confusion Matrix

The project also discusses:

* Underfitting
* Overfitting
* Model generalization

---

## 📉 Visualizations

The project includes several visualizations, such as:

* Flight delay distributions
* Flight distance distributions
* Boxplots
* Scatter plots
* Pair plots
* Correlation heatmap
* Arrival delay density plot
* Average arrival delay by carrier
* Classification confusion matrix

---

## 📂 Project Structure

```text
flight-data-analysis/
│
├── data_analytics_project_v2.ipynb
├── flights.csv
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/flight-data-analysis.git
```

### 2. Navigate to the project directory

```bash
cd flight-data-analysis
```

### 3. Install required libraries

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
data_analytics_project_v2.ipynb
```

Make sure `flights.csv` is located in the same directory as the notebook.

---

## 📚 Dataset

The analysis is performed on a flight dataset containing information related to flight schedules, carriers, routes, delays, distance, air time, and other flight attributes.

---

## 🎓 Academic Project

This project was developed as a **Semester Python / Data Analytics project** to demonstrate practical knowledge of:

**Python → Data Analysis → Data Visualization → Statistics → Machine Learning**

---

## 👨‍💻 Author

**Raj Maiyani**

Bachelor of Computer Applications (BCA)

---

## ⭐ Skills Demonstrated

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Scikit-learn` `EDA` `Data Visualization` `Statistics` `Linear Regression` `Logistic Regression` `Machine Learning`
