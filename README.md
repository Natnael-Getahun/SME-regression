# Factors Affecting the Current Capital of MSEs: A Multiple Linear Regression Approach

## Overview
This project investigates the determinants of current capital for Micro and Small Enterprises (MSEs) in Ethiopia using multiple linear regression analysis. The study explores the impact of various factors such as initial capital, years of establishment, education level, and gender on the financial growth of MSEs.

## Project Structure
The repository is organized as follows:

*   **data/**: Contains the dataset used for analysis (`Project data.xls`).
*   **docs/**: Documentation files including the full written project report and original assignment guidelines.
*   **notebooks/**: Jupyter notebooks containing the data analysis, visualization, and regression modeling.
*   **requirements.txt**: List of Python dependencies required to run the analysis.

## Analysis Summary
The analysis proceeds through several stages:
1.  **Exploratory Data Analysis (EDA)**: Visualizing distributions and relationships between variables.
2.  **Model Building**:
    *   Initial Ordinary Least Squares (OLS) model.
    *   Log-transformed OLS model to address skewness.
    *   Weighted Least Squares (WLS) model to correct for heteroscedasticity.
3.  **Key Findings**:
    *   Initial capital is the strongest predictor of current capital.
    *   Female owners tend to have lower current capital compared to male owners.
    *   Years of schooling shows a positive relationship with current capital.

## Usage
1.  Clone the repository.
2.  Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3.  Navigate to the `notebooks/` directory and launch Jupyter Notebook to view `Econometrics_Analysis.ipynb`.

## Authors
Natnael G. Mengistu, Yoseph H. Tilahun, Yonas D. Melese, Abenezer Y. Bekele, Fitsum A. Zewude, Rahel D. Shikur

Department of Statistics, College of Natural and Computational Sciences, Addis Ababa University.
