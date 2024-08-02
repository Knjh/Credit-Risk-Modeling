# Credit Risk Modeling using Machine Learning

## Project Overview

This project aims to classify customers into four categories (p1, p2, p3, p4) based on their credit risk. The classification helps determine the best candidates for loan approvals, with:
- `p1` representing the best candidates for loans,
- `p2` representing the second best,
- `p3` representing the third best,
- `p4` representing the least favorable candidates.

The project utilizes customer CIBIL data and bank-related history to build a predictive model.

## Data

The project uses two separate data files:
1. **Customer CIBIL Data**: Contains credit information of customers.
2. **Bank-Related History Data**: Contains historical banking information of customers.

## Methodology

1. **Data Preprocessing**: 
   - Data cleaning
   - Handling missing values
   - Data normalization

2. **Feature Selection**: 
   - **Hypothesis Testing**:
     - Chi-square test
     - ANOVA test
   - **Variance Inflation Factor (VIF)**: To check multicollinearity among features.

3. **Modeling**:
   - Various machine learning algorithms are explored, with a focus on `XGBoost` for classification.
