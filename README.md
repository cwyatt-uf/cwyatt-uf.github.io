# Cullen Wyatt - Chemical Process Data Science Project

Chemical Engineering, University of Florida

---

## Project: Predicting Future Financial Distress from key Financial Metrics 
**The question.** Can we predict financial distress in companies based on historical financial metrics?

**The data.** Financial metrics for members of the S&P 500, S&P 400 and S&P 600 from 2007 to 2023 (pulled from Refinitiv).

**What I did.**
1. Cleaned the data to remove financial institutions and firm-years where a company was not in one of the three indices
2. Fitted a regression model
3. Tested it on data the model had never seen

**What I found.** A random forest beat logistic regression and the Altman Z-score on held-out 2017–2023 data (ROC-AUC 0.905 vs. 0.888 and 0.703). Reviewing the riskiest 5% of firms each year catches 57% of next-year distress cases. Early warning for currently healthy firms remains hard (ROC-AUC 0.83).

### Notebooks
- [1. Building the Model](https://github.com/cwyatt-uf/cwyatt-uf.github.io/blob/main/notebooks/Distress_Prediction_Notebook.ipynb)

---

## About me

Fourth-year chemical engineering student pursuing a career in investment banking.