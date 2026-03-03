# Predicting SME Bankruptcy in France: A Machine Learning Approach to Macro-Micro Dynamics

## Project Overview
This repository contains the research and implementation of my Master's Thesis at IÉSEG School of Management. The study focuses on bridging the gap between firm-level accounting indicators and macroeconomic shocks (ECB interest rate shifts) to predict SME failures in France.

**Key Achievement:** Developed a predictive model that maintains robustness across structural economic shifts, achieving an **AUC of 0.68** in a restrictive monetary regime.

## Key Features
- **Macro-Micro Integration:** Integrated high-dimensional macroeconomic temporal shifts with micro-level financial ratios.
- **Advanced ML Pipeline:** Benchmarking XGBoost, LightGBM, and Random Forest.
- **Explainable AI (XAI):** Utilized **SHAP** and **Grad-CAM** to interpret "black-box" models and identify the "Debt-Interest Interaction" as a top-3 failure determinant.
- **Systemic Risk Analysis:** Identified a high-risk concentration of €39.79 Billion in systemic debt-at-risk among French SMEs.

## Tech Stack
- **Languages:** Python (Pandas, NumPy, Scikit-learn)
- **Models:** XGBoost, LightGBM, Random Forest
- **Interpretability:** SHAP, Matplotlib, Seaborn
- **Data Engineering:** Large-scale data merging (268,000+ entities from Orbis)

## Results Summary
- **AUC-ROC:** 0.68 (Out-of-Time test set).
- **Key Insight:** Over-optimization on historical data from low-interest regimes (2016-2022) leads to performance degradation (AUC 0.57) during restrictive cycles.
- **Top Predictors:** Total Assets (Scale), Debt Ratio (Leverage), and the interaction between Interest Rates and Debt.

## 📂 Repository Structure
- `notebooks/`: Contains the end-to-end data merging and modeling pipeline.
- `docs/`: Full Thesis PDF and Defense Presentation slides.

## Contact
**Son Quy DAM** - [LinkedIn](https://linkedin.com/in/damsonquy/) - damsonquy@gmail.com
