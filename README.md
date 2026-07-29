# CS4503: Data Analytics and Visualization Lab

This repository contains the complete codebase, datasets, and executed Jupyter Notebooks for the Data Analytics and Visualization Lab (Experiments 1 to 5).

---

## 📂 Repository Structure

The project is organized into self-contained directories for each experiment:

```text
DAV_Lab/
├── .gitattributes             # Line ending normalization and binary flags
├── .gitignore                 # Files excluded from Git tracking
├── DAV manual UPDATED.pdf     # Original Lab Manual
├── README.md                  # Project documentation
│
├── Experiment_1/              # Lab Environment Verification
│   ├── Experiment_1.ipynb     # Executed Jupyter Notebook
│   └── experiment_1.py        # Python script format
│
├── Experiment_2/              # Data Handling and Analytics
│   ├── Experiment_2.ipynb     # Jupyter Notebook (Parts A, B, C, D)
│   ├── experiment_2_a.py      # Part A: NumPy Array Operations
│   ├── experiment_2_b.py      # Part B: Pandas DataFrame Operations
│   ├── experiment_2_c.py      # Part C: Multi-source File Reading
│   ├── experiment_2_d.py      # Part D: Iris Descriptive Analytics
│   └── datasets / data files  # data.csv, Google_data (2b.c1).csv, data (2c2).xlsx, iris_dataset(2d).csv
│
├── Experiment_3/              # Statistical Analysis on Diabetes Datasets
│   ├── Experiment_3.ipynb     # Jupyter Notebook (Parts A, B, C, D)
│   ├── experiment_3_a.py      # Part A: Univariate Analysis
│   ├── experiment_3_b.py      # Part B: Bivariate Regression (Linear & Logistic)
│   ├── experiment_3_c.py      # Part C: Multiple Linear Regression
│   └── datasets / data files  # uci_diabetes.csv, pima_diabetes.csv
│
├── Experiment_4/              # Data Visualization and Hypothesis Testing
│   ├── Experiment_4.ipynb     # Jupyter Notebook (Parts A, B, C, D)
│   └── datasets / data files  # uci_diabetes (3).csv, pima_diabetes (3).csv
│
└── Experiment_5/              # Model Building and Time Series Forecasting
    ├── Experiment_5.ipynb     # Jupyter Notebook (Parts A, B, C)
    └── datasets / data files  # uci_diabetes (3).csv, pima_diabetes (3).csv, diabetes9.csv
```

---

## 🧪 Experiments Summary

### [Experiment 1: Installation & Library Verification](Experiment_1/Experiment_1.ipynb)
- **Objective:** Establish the lab environment and verify versions of critical libraries.
- **Libraries Verified:** `numpy`, `pandas`, `matplotlib`, `seaborn`, `statsmodels`, `scipy`, `plotly`, `bokeh`, `jupyterlab`.

### [Experiment 2: Data Handling & Analysis](Experiment_2/Experiment_2.ipynb)
- **Part A:** NumPy array manipulation (slicing, indexing, aggregations, boolean masking, fancy indexing, reshaping, structured arrays).
- **Part B:** Pandas DataFrame operations (loading, inspecting, missing values imputation, filtering, grouping, sorting, duplicate removal, saving subsets).
- **Part C:** Loading data from CSV, Excel, and HTTPS endpoints, handling forward-fill (`ffill`), backward-fill (`bfill`), and outputting processed datasets.
- **Part D:** Descriptive analytics using the Iris dataset, plotting feature distributions (Histograms), Sepal Length comparisons (Boxplots), and Pairwise relations (Pairplots).

### [Experiment 3: Statistical Analysis using Diabetes Datasets](Experiment_3/Experiment_3.ipynb)
- **Part A:** Univariate Analysis calculating Frequency, Mean, Median, Mode, Variance, Standard Deviation, Skewness, and Kurtosis.
- **Part B:** Bivariate Analysis implementing Linear Regression (Glucose vs. BMI) and Binary Logistic Regression (Outcome prediction).
- **Part C:** Multiple Linear Regression modeling (Glucose, Blood Pressure, and Age vs. BMI).
- **Part D:** Detailed statistical comparison of outcomes and model performances between the UCI and Pima Indians diabetes datasets.

### [Experiment 4: Hypothesis Testing on Diabetes Datasets](Experiment_4/Experiment_4.ipynb)
- **Part A:** Fitting and plotting Normal Distribution Curves overlaying key feature KDEs (Glucose and BMI).
- **Part B:** Z-test to evaluate if the mean Glucose level significantly differs from the population mean of 100.
- **Part C:** Unpaired Independent T-test to compare feature means between UCI and Pima Indians diabetes datasets.
- **Part D:** One-Way ANOVA to evaluate variation across multiple group means.

### [Experiment 5: Model Building, Validation & Time Series](Experiment_5/Experiment_5.ipynb)
- **Part A:** Building and validating Multiple Linear Regression models (predicting Age) using $R^2$, MSE, and MAE.
- **Part B:** Building and validating Binary Logistic Regression classifiers (predicting Outcome) and plotting Confusion Matrices.
- **Part C:** Time Series Decomposition (Trend, Seasonality, Residuals) of sequential glucose measurements, 7-day Moving Average smoothing, and ARIMA model forecasting.

---

## 🛠️ Getting Started

### Prerequisites

To run these notebooks, install the required packages:

```bash
pip install numpy scipy jupyter statsmodels pandas matplotlib seaborn plotly bokeh openpyxl
```

### Running the Notebooks

1. Start Jupyter Lab:
   ```bash
   jupyter lab
   ```
2. Open any of the experiment folders and double-click the `.ipynb` file to run cells interactively.
