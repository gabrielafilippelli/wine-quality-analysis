# Wine Quality Analysis (Red vs White)

## Project Overview
This project explores the physicochemical factors that influence wine quality, using two datasets of **red and white vinho verde wines** from Portugal. The analysis focuses on identifying which attributes are most strongly associated with quality scores and how these relationships differ between wine types.

The project emphasizes **exploratory data analysis, comparative analysis, and data visualization** using Python.

---

## Dataset
- Source: UCI Machine Learning Repository  
- Observations:  
  - Red wine samples  
  - White wine samples  
- Target Variable: `quality` (integer score from 1–10)

**Citation:**  
Paulo Cortez et al., *Modeling wine preferences by data mining from physicochemical properties*, Decision Support Systems (2009).

---

## Tools & Technologies
- Python 3.8  
- pandas, NumPy  
- matplotlib, seaborn  
- Jupyter Notebook  

---

## Analytical Questions
- Which physicochemical properties are most strongly associated with wine quality?
- Do the drivers of quality differ between red and white wines?
- Are there notable patterns or tradeoffs among acidity, alcohol content, and sulfur compounds?

---

## Analysis Approach
- Data cleaning and validation  
- Univariate and multivariate exploratory analysis  
- Correlation analysis  
- Comparative visualization between red and white wine datasets  

---

## Key Findings (Summary)
- Alcohol content shows a strong positive association with quality across both wine types.
- Volatile acidity is negatively associated with quality, particularly for red wines.
- White and red wines exhibit different sensitivity to sulfur dioxide and acidity levels.
- Several features show nonlinear or interaction effects that differ by wine type.

---

## Repository Structure
- `Red Wine Quality Analysis.ipynb` — EDA focused on red wine samples  
- `White Wine Quality Analysis.ipynb` — EDA focused on white wine samples  
- `White Wine vs Red Wine Data Analysis.ipynb` — Comparative analysis  

---

## Limitations & Next Steps
- Analysis is descriptive and exploratory; no predictive modeling is implemented.
- Future work could include regression or classification models to predict quality scores and quantify feature importance.

---

## Author
Gabriela Filippelli
