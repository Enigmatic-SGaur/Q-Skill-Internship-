# Q-Skills Slab 1: Python Data Science & Analytics

This repository contains solutions for the **Slab 1 [For Beginners]** tasks. The projects cover foundational data manipulation, exploratory data analysis, predictive modeling using Scikit-Learn, and interactive tool development with NumPy and `ipywidgets`.

---

## 📌 Tasks Overview

### Task 1: Exploratory Data Analysis & Visualization
* **Objective:** Perform exploratory data analysis (EDA) on structured dataset columns and plot key visual metrics.
* **Key Features:**
  * Summary statistics calculation (column averages, standard deviations).
  * Data visualization using Matplotlib and Seaborn (Bar Chart, Scatter Plot, Heatmap correlation matrix).
  * Key observations and analytical insights printout.
* **Tools Used:** `Pandas`, `Matplotlib`, `Seaborn`

---

### Task 2: House Price Prediction (Linear Regression)
* **Objective:** Build a regression model to predict housing prices using real-world data fetched directly from Kaggle (Ames Housing Dataset).
* **Key Features:**
  * Preprocessing pipeline: Missing value imputation, one-hot encoding for categorical variables (Neighborhood/Location), and feature scaling via `StandardScaler`.
  * Train-test splitting and model training using `LinearRegression`.
  * Model evaluation using MAE, RMSE, and $R^2$ score along with actual vs. predicted price plots.
* **Tools Used:** `Pandas`, `Scikit-Learn`, `Matplotlib`

---

### Task 3: Interactive Matrix Operations Tool
* **Objective:** Develop a user-friendly matrix processing utility.
* **Key Features:**
  * Handles matrix Addition, Subtraction, Multiplication, Transposition, and Determinant calculations.
  * Interactive UI using `ipywidgets` inside Google Colab for user input and real-time execution.
* **Tools Used:** `NumPy`, `ipywidgets`

---

## 🚀 How to Run in Google Colab

1. Click on any `.ipynb` notebook in this repository.
2. Click the **Open in Colab** badge at the top of the file, or download the notebook and open it manually at [colab.research.google.com](https://colab.research.google.com).
3. Run the code cells sequentially (`Shift + Enter`).
