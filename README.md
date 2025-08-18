### URL: [Projekt-Repository: Regression Monetary Freedom](https://github.com/Jannik-m12/Regression-Monetary-Freedom)

# 📊 Economic Freedom & Human Development

## 📝 Summary
This project investigates the relationship between **economic freedom**, as measured by the *Economic Freedom of the World (EFW) Index* from the Fraser Institute, and the **Human Development Index (HDI)** published by the United Nations Development Programme (UNDP).  

The goal is to understand which dimensions of economic freedom—such as property rights, government size, trade openness, sound money, and regulation—are most strongly associated with the **well-being of the average citizen**. By linking economic freedom to HDI, this study goes beyond traditional GDP-based measures of wealth, capturing broader aspects of human development including health, education, and income.  

Understanding these relationships matters because it can inform **policy decisions** and **institutional reforms**. If certain aspects of economic freedom—like secure property rights or efficient regulation—are strongly associated with higher HDI scores, governments and policymakers can target reforms in these areas to promote sustainable human development. Conversely, identifying dimensions with weaker or negative effects can help avoid policies that may hinder overall well-being.  

In short, this analysis sheds light on how **economic structures and institutions impact the everyday lives of citizens**, providing evidence for designing policies that foster both economic freedom and human development.
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

## Project Goal
Analyze how Economic Freedom affects human development and identify key patterns.(Economic Freedom of the World (EFW) – Fraser Institute).

---

## Data Source

- **Economic Freedom of the World (EFW) – Fraser Institute**  
  [https://efotw.org/economic-freedom/dataset](https://efotw.org/economic-freedom/dataset?geozone=world&year=2022&page=dataset&min-year=2&max-year=0&filter=0)

- **Human Development Index (HDI) – United Nations Development Programme (UNDP)**  
  [https://hdr.undp.org/data-center/human-development-index](https://hdr.undp.org/data-center/human-development-index#/indicies/HDI)

### Quality
- **EFW**: Compiled by the Fraser Institute using robust, transparent methodologies and internationally comparable indicators from reliable sources such as the World Bank, IMF, and national statistical agencies.  
- **HDI**: Published annually by the UNDP, using standardized, high-quality data from international agencies. Both datasets are widely cited in academic research and policy reports, ensuring credibility and reproducibility.

### Sustainability and Social Impact
- Insights derived from these datasets can inform policy reforms that promote **inclusive economic growth**, strengthen institutions, and improve social outcomes.  
- By identifying which dimensions of economic freedom most strongly correlate with human development, the analysis has potential **long-term societal benefits**, guiding governments and international organizations to design policies that enhance human welfare sustainably.

### Licensing
- **EFW Dataset**: Freely available for academic and non-commercial research; proper citation of the Fraser Institute is required.  
- **HDI Dataset**: Open-access data provided by the UNDP under standard attribution guidelines, suitable for research, teaching, and public use.  

### These datasets are therefore highly suitable for rigorous, socially impactful research on the intersection of economic freedom and human development.
---

## Dependencies
Listed in `requirements.txt`

---

## Contact
Jannik Melcher (jannikm2002@gmail.com)

### URL: [Projekt-Repository: Regression Monetary Freedom](https://github.com/Jannik-m12/Regression-Monetary-Freedom)

# 📊 Economic Freedom & Human Development

## 📝 Summary
This project investigates the relationship between **economic freedom**, as measured by the *Economic Freedom of the World (EFW) Index* from the Fraser Institute, and the **Human Development Index (HDI)** published by the United Nations Development Programme (UNDP).  

The goal is to understand which dimensions of economic freedom—such as property rights, government size, trade openness, sound money, and regulation—are most strongly associated with the **well-being of the average citizen**. By linking economic freedom to HDI, this study goes beyond traditional GDP-based measures of wealth, capturing broader aspects of human development including health, education, and income.  

Understanding these relationships matters because it can inform **policy decisions** and **institutional reforms**. If certain aspects of economic freedom—like secure property rights or efficient regulation—are strongly associated with higher HDI scores, governments and policymakers can target reforms in these areas to promote sustainable human development. Conversely, identifying dimensions with weaker or negative effects can help avoid policies that may hinder overall well-being.  

### In short, this analysis sheds light on how economic structures and institutions impact the everyday lives of citizens, providing evidence for designing policies that foster both economic freedom and human development.
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

## Project Goal
Analyze how Economic Freedom affects human development and identify key patterns.(Economic Freedom of the World (EFW) – Fraser Institute).

---

## Data Source

- **Economic Freedom of the World (EFW) – Fraser Institute**  
  [https://efotw.org/economic-freedom/dataset](https://efotw.org/economic-freedom/dataset?geozone=world&year=2022&page=dataset&min-year=2&max-year=0&filter=0)

- **Human Development Index (HDI) – United Nations Development Programme (UNDP)**  
  [https://hdr.undp.org/data-center/human-development-index](https://hdr.undp.org/data-center/human-development-index#/indicies/HDI)

---

## Dependencies
Listed in `requirements.txt`

---

## Contact
Jannik Melcher (jannikm2002@gmail.com)

