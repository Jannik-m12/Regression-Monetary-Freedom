### URL: [Projekt-Repository: Regression Monetary Freedom](https://github.com/Jannik-m12/Regression-Monetary-Freedom)

# Regression-Monetary-Freedom - Jannik Melcher

This project explores the role of Monetary Freedom in shaping overall Economic Freedom across countries. Using the Heritage Foundation’s Index of Economic Freedom (1995–2024), we analyze whether lower Monetary Freedom scores are associated with weaker performance in other dimensions of economic freedom. The goal is to uncover patterns and insights that can inform policy discussions and economic research.

| **Section** | **Purpose** |
| --- | --- |
| **Project Title** | Monetary Freedom is Key for Economic Freedom |
| **Summary** | This project investigates the relationship between Monetary Freedom and overall Economic Freedom. By analyzing the Heritage Foundation’s Index of Economic Freedom dataset, we aim to determine whether countries with lower Monetary Freedom scores also tend to have lower overall economic freedom. Understanding this relationship is important for policymakers and economists, as it highlights the potential impact of monetary policy and regulatory stability on broader economic conditions. |
| **Hypothesis** | Countries with low Monetary Freedom tend to have a lower overall Index of Economic Freedom. |
| **Dataset Info** | The dataset comes from the Heritage Foundation (1995–2024) and includes the overall Index of Economic Freedom and 12 sub-indices for approximately 180 countries annually. Relevant sub-indices include Property Rights, Judicial Effectiveness, Government Integrity, Tax Burden, Government Spending, Fiscal Health, Business Freedom, Labor Freedom, Monetary Freedom, Trade Freedom, Investment Freedom, and Financial Freedom. |
| **Installation** | 1. Clone the repository: <br>```bash<br>git clone https://github.com/Jannik-m12/Regression-Monetary-Freedom.git<br>```<br>2. Navigate to the project folder: <br>```bash<br>cd Regression-Monetary-Freedom<br>```<br>3. Install dependencies: <br>```bash<br>pip install -r requirements.txt<br>``` |
| **Usage** | - Navigate to the project folder: <br>```bash<br>cd Regression-Monetary-Freedom<br>```<br>- Run the data exploration notebook first: <br>```bash<br>jupyter notebook notebooks/01-exploration.ipynb<br>```<br>- Then run the regression analysis notebook: <br>```bash<br>jupyter notebook notebooks/02-modeling.ipynb<br>```<br>- Check the outputs:<br>  - `outputs/figures/` for visualizations showing trends and correlations<br>  - `outputs/report/` for summary tables and regression results |
| **Folder Structure** | ```<br>Regression-Monetary-Freedom/<br>├── Data/<br>│   ├── Raw/            # Original raw dataset files<br>│   └── Processed/      # Cleaned and processed datasets<br>├── Notebooks/<br>│   ├── 01-exploration.ipynb   # Data exploration and visualization<br>│   └── 02-modeling.ipynb      # Regression analysis on Monetary Freedom vs. overall IEF<br>├── outputs/<br>│   ├── figures/        # Plots showing trends and correlations<br>│   └── report/         # Summary tables and regression results<br>├── src/<br>│   └── utils.py        # Helper functions and utilities<br>├── requirements.txt    # List of Python packages needed<br>└── README.md           # This file<br>``` |
| **Ethical Notes** | The project uses publicly available country-level data; no personal data is involved. Conclusions about country performance should be interpreted carefully to avoid stigmatizing nations or policymakers. The analysis is descriptive and intended to inform economic research and policy discussion. |


## Project Goal
Analyze how Monetary Freedom affects overall Economic Freedom and identify key patterns in the Heritage Foundation dataset (1995–2024).

## Data Source
Heritage Foundation – Index of Economic Freedom (https://www.heritage.org/index/)

## Dependencies
Listed in `requirements.txt`

## Contact
Jannik Melcher (jannikm2002@gmail.com)

