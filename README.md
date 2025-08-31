### URL: [Projekt-Repository: Regression Monetary Freedom](https://github.com/Jannik-m12/Regression-Monetary-Freedom)

| **Section** | **Purpose** |
| --- | --- |
| **Project Title** | Monetary Freedom is Key for Economic Freedom |
| **Summary** | This project investigates the relationship between Monetary Freedom and overall Economic Freedom. By analyzing the Heritage Foundation’s Index of Economic Freedom dataset, we aim to determine whether countries with lower Monetary Freedom scores also tend to have lower overall economic freedom. Understanding this relationship is important for policymakers and economists, as it highlights the potential impact of monetary policy and regulatory stability on broader economic conditions. |
| **Hypothesis** | Countries with low Monetary Freedom tend to have a lower overall Index of Economic Freedom. |
| **Dataset Info** | The dataset comes from the Heritage Foundation (1995–2024) and includes the overall Index of Economic Freedom and 12 sub-indices for approximately 180 countries annually. Relevant sub-indices include Property Rights, Judicial Effectiveness, Government Integrity, Tax Burden, Government Spending, Fiscal Health, Business Freedom, Labor Freedom, Monetary Freedom, Trade Freedom, Investment Freedom, and Financial Freedom. |
| **Installation** | 1. Clone the repository: `git clone <repo_url>`<br>2. Navigate to the project folder: `cd <project_folder>`<br>3. Install dependencies: `pip install -r requirements.txt` |
| **Usage** | - Run `notebooks/analysis.ipynb` to explore the dataset and reproduce regression results.<br>- Use `scripts/monetary_freedom_regression.py` to run regression analysis on Monetary Freedom vs. overall IEF (excluding Monetary Freedom).<br>- Results include tables of regression coefficients, summary statistics, and plots showing trends and correlations. |
| **Folder Structure** | ```<br>/data - raw and processed dataset files<br>/notebooks - Jupyter notebooks for exploration and analysis<br>/scripts - Python scripts for regression and plotting<br>/results - regression outputs, tables, and figures<br>requirements.txt - dependencies<br>README.md - this file<br>``` |
| **Ethical Notes** | The project uses publicly available country-level data; no personal data is involved. Conclusions about country performance should be interpreted carefully to avoid stigmatizing nations or policymakers. The analysis is descriptive and intended to inform economic research and policy discussion. |

# Monetary Freedom Project

## Project Goal
Analyze how Monetary Freedom affects overall Economic Freedom and identify key patterns in the Heritage Foundation dataset (1995–2024).

## Data Source
Heritage Foundation – Index of Economic Freedom (https://www.heritage.org/index/)

## How to Run
1. Clone the repo  
2. Run `notebooks/analysis.ipynb`  
3. See `results/` folder for regression outputs and plots  

## Dependencies
Listed in `requirements.txt`

## Contact
Jannik Melcher (jannikm2002@gmail.com)


