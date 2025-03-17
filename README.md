# Comparative-Analysis-of-AMD-and-Intel-Risk-Return-and-Market-Performance
## **Project Overview**
This project aims to analyze and compare **Advanced Micro Devices (AMD)** and **Intel (INTC)** in terms of their **stock performance, risk-adjusted returns, and market correlation**. The study evaluates the **excess returns**, calculates **Sharpe Ratios**, and examines **regression models** to understand how these semiconductor giants move in relation to the NASDAQ index.

## **Project Objectives**
- Assess the **risk-adjusted returns** of AMD and Intel.
- Determine whether AMD and Intel stocks are **directly comparable**.
- Evaluate how both stocks correlate with the **NASDAQ index**.
- Analyze the statistical significance of **beta values** using regression models.

## **Why Compare AMD and Intel?**
- Both companies operate in the **semiconductor industry** and compete in **CPU, GPU, and data center markets**.
- They respond to **macroeconomic factors**, making them key players in tech-driven stock movements.
- Comparing their **risk-adjusted returns** helps investors determine which stock provides better compensation for risk.

## **Methodology**
1. **Data Collection:**  
   - Obtained daily closing prices for AMD, Intel, and NASDAQ.
   - Retrieved **3-Month Treasury Bill** (risk-free rate) for excess return calculations.
   
2. **Excess Return Calculation:**  
   - **Excess Return = Stock Return - Risk-Free Rate** (for AMD, Intel, and NASDAQ).
   
3. **Regression Analysis (OLS Model):**  
   - **Dependent Variable:** Excess return of AMD or Intel.  
   - **Independent Variable:** Excess return of NASDAQ.  
   - **Objective:** Measure beta coefficients and statistical significance.  

4. **Sharpe Ratio Calculation:**  
   - **Sharpe Ratio = (Mean Excess Return) / (Standard Deviation of Excess Return)**  
   - Used to assess which stock provides better risk-adjusted returns.

## **Key Findings**
- **Beta Values:**  
  - **AMD Beta:** 1.54 (Statistically significant, p < 0.01)  
  - **Intel Beta:** 1.44 (Statistically significant, p < 0.01)  
  - Both stocks show a strong positive correlation with the NASDAQ index.  

- **Sharpe Ratios:**  
  - **AMD:** -0.0863 (Lower risk-adjusted performance)  
  - **Intel:** -0.0513 (Slightly better risk-adjusted performance)  
  - Both stocks had negative Sharpe Ratios, indicating excess returns did not sufficiently compensate for risk.

## **Conclusion**
- **Intel shows slightly better risk-adjusted returns** than AMD based on Sharpe Ratios.
- **AMD has a higher beta**, meaning it is more volatile and reactive to NASDAQ movements.
- **Both stocks are directly comparable**, but their business models and market positioning influence their returns differently.

## **Technologies Used**
- **Python** (Pandas, NumPy, Statsmodels, Matplotlib, FredAPI)
- **Data Sources:** Yahoo Finance, FRED Economic Data

## **Future Work**
- Extend the analysis with **Machine Learning models** for price prediction.
- Compare AMD and Intel with other tech giants like **NVIDIA**.
- Explore the impact of **macroeconomic factors** like interest rates and inflation.

## **Author**
- **Charan Kumar Pathakamuri**  
- M.S. in Data Science, University of Maryland, Baltimore County (UMBC)  
