# 📊 Economic Freedom & Human Development

## 📝 Summary
This project explores the relationship between **economic freedom** (measured by the *Economic Freedom of the World Index* from the Fraser Institute) and the **Human Development Index (HDI)** published by the United Nations Development Programme (UNDP).  
The goal is to investigate which dimensions of economic freedom are most strongly associated with the **well-being of the average citizen**.

---

## 💡 Hypothesis
- Countries with higher levels of economic freedom tend to have a higher HDI.  

---

## 📂 Dataset Info

### Economic Freedom of the World (EFW) – Fraser Institute
- Source: [Fraser Institute Dataset](https://www.fraserinstitute.org/economic-freedom/dataset)  
- Coverage: up to 165 countries, years **1970–2022** (with gaps)  
- Structure:  
  - **Overall Index** (0–10 scale)  
  - **5 Main Areas**:  
    1. Government Size  
    2. Legal System & Property Rights  
    3. Sound Money  
    4. Freedom to Trade Internationally  
    5. Regulation  

### Human Development Index (HDI) – UNDP
- Source: [UNDP Human Development Data](https://hdr.undp.org/data-center/documentation-and-downloads)  
- Coverage: ~190 countries, years **1990–2022**  
- Structure:  
  - **HDI score** (0–1 scale)  
  - Subindices: Life expectancy, Education, Income  

---

## 🔍 Research Questions
1. Is there a statistically significant relationship between the **EFW score** and the **HDI**?  
2. Which of the **5 subcomponents** of the EFW best explains differences in HDI?  
3. Do the effects differ between country groups (e.g., developed vs. developing countries)?  

---

## ⚙️ Methodology (Planned)
- Merge **EFW Index** and **HDI** by country and year  
- Run **cross-sectional regressions** (one year, many countries)  
- Run **panel regressions with fixed effects** (multiple years, many countries)  
- Compare the influence of the 5 EFW subindices  

---













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
| **Folder Structure** | ```Regression-Monetary-Freedom/├── Data/│   ├── Raw/            # Original raw dataset files│   └── Processed/      # Cleaned and processed datasets├── Notebooks/│   ├── 01-exploration.ipynb   # Data exploration and visualization│   └── 02-modeling.ipynb      # Regression analysis on Monetary Freedom vs. overall IEF├── outputs/│   ├── figures/        # Plots showing trends and correlations│   └── report/         # Summary tables and regression results├── src/│   └── utils.py        # Helper functions and utilities├── requirements.txt    # List of Python packages needed└── README.md           # This file``` |
| **Ethical Notes** | The project uses publicly available country-level data; no personal data is involved. Conclusions about country performance should be interpreted carefully to avoid stigmatizing nations or policymakers. The analysis is descriptive and intended to inform economic research and policy discussion. |


## Project Goal
Analyze how Economic Freedom affects human development and identify key patterns.(Economic Freedom of the World (EFW) – Fraser Institute).

## Data Source
Economic Freedom of the World (EFW) – Fraser Institute - (https://efotw.org/economic-freedom/dataset?geozone=world&year=2022&page=dataset&min-year=2&max-year=0&filter=0)
Human Development Index (HDI) - United Nations Development Programme (UNDP) - (https://hdr.undp.org/data-center/human-development-index#/indicies/HDI)

## Dependencies
Listed in `requirements.txt`

## Contact
Jannik Melcher (jannikm2002@gmail.com)

