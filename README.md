# Homoscedasticity in Regression Analysis

Homoscedasticity the assumption that regression disturbances share a constant variance — is a fundamental requirement for valid inference in Ordinary Least Squares (OLS) models.

This project provides a rigorous, self-contained exploration of the main statistical tests used to assess this assumption.

---

## 📌 Overview

In regression analysis, violating the homoscedasticity assumption can lead to:
- Biased standard errors
- Invalid hypothesis tests
- Misleading confidence intervals

This report focuses on detecting heteroscedasticity using formal statistical methods and provides practical guidance for their application.

---

## 📊 Covered Tests

The following homoscedasticity tests are examined in detail:

### 1. Breusch–Pagan / Koenker Test
- Based on auxiliary regression
- Detects linear forms of heteroscedasticity
- Koenker version is robust to non-normality

### 2. White’s Test
- A general test with no specific functional form
- Captures nonlinear and interaction effects
- Widely used due to flexibility

### 3. Goldfeld–Quandt Test
- Compares variances across two subgroups
- Requires ordering of observations
- Sensitive to how data is split

### 4. Park Test
- Assumes a specific functional relationship between variance and regressors
- Simpler but more restrictive

---

## ⚙️ What This Project Provides

- Mathematical foundations of each test  
- Step-by-step implementation guidance  
- Interpretation of results  
- Strengths and limitations of each method  
- A comparative framework to choose the right test  
- A practical diagnostic workflow for real-world applications  

---

## 🔄 Diagnostic Workflow

A suggested approach for practitioners:

1. **Start with visual inspection**
   - Residual plots
2. **Apply general tests**
   - White’s Test
3. **Use targeted tests**
   - Breusch–Pagan (for linear patterns)
4. **Validate with alternative methods**
   - Goldfeld–Quandt or Park test
5. **Take corrective action if needed**
   - Robust standard errors
   - Transformations
   - Model re-specification

---

## 🚀 Applications

This work is useful for:
- Econometrics
- Financial modeling
- Machine learning regression diagnostics
- Data science workflows

---

## 🔗 Reference

For additional resources, visit:  
[1] Breusch, T. S. and Pagan, A. R. (1979). A simple test for heteroscedasticity and
random coefficient variation. Econometrica, 47(5), 1287–1294.

[2] Engle, R. F. (1982). Autoregressive conditional heteroscedasticity with estimates of
the variance of United Kingdom inflation. Econometrica, 50(4), 987–1007.

[3] Goldfeld, S. M. and Quandt, R. E. (1965). Some tests for homoscedasticity. Journal
of the American Statistical Association, 60(310), 539–547.

[4] Koenker, R. (1981). A note on studentizing a test for heteroscedasticity. Journal of
Econometrics, 17(1), 107–112.

[5] MacKinnon, J. G. and White, H. (1985). Some heteroskedasticity-consistent covari-
ance matrix estimators with improved finite sample properties. Journal of Econo-
metrics, 29(3), 305–325.

[6] Park, R. E. (1966). Estimation with heteroscedastic error terms. Econometrica, 34(4),
888.

