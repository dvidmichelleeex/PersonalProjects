# **Regression Analysis in Excel Project**

This repository contains the **Regression Analysis in Excel Project**, a comprehensive analysis of the relationship between variables such as Discount, Product Price, and Total Amount Spent. The project applies correlation analysis, simple linear regression, multiple linear regression, and predictive modeling to analyze the dataset. The analysis and insights were generated using Excel.

---

## **Project Overview**

The **Regression Analysis in Excel Project** provides insights into the following:
- **Correlation Analysis**: Understanding the relationship between variables.
- **Simple Linear Regression**: Examining the impact of Discount on Total Amount Spent.
- **Multiple Linear Regression**: Refining the model by including Product Price and additional variables as predictors.
- **Advanced Regression**: Handling multicollinearity and using categorical data to build an optimized regression model.
- **Predictive Modeling**: Using the regression model to predict outcomes and assess model performance.

---

## **Goal**

The goal of this project is to analyze the factors influencing the Total Amount Spent and to develop a predictive model that can be used for business decision-making and forecasting.

---

## **Tools Used**

- **Excel**: For data cleaning, analysis, and visualization.
- **Power Query**: For advanced data cleaning and transformation.

---

## **Dataset**

The dataset contains:
- Variables such as Discount, Product Price, and Total Amount Spent.
- Categorical data such as User Region, Product Category, and Gender.
---

## **Tasks and Insights**

### **Task 1: Correlation Analysis**
- **Key Insight**: A weak positive correlation exists between Discount and Total Amount Spent. The scatter plot suggests a non-linear relationship, with outliers affecting accuracy.

---

### **Task 2: Simple Linear Regression**
- **Regression Line Equation**: 
  \[
  Y = 127.2927 + 0.75069 \times \text{Discount}
  \]
- **Key Findings**:
  - Slope = `0.75069`: For every 1-unit increase in Discount, the Total Amount Spent increases by 0.75069.
  - Intercept = `127.2927`: When Discount is 0, the predicted Total Amount Spent is 127.2927.
  - **Model Fit**: The regression shows a weak positive correlation, with only 16.5% of the variance in Total Amount Spent explained by Discount. Additional variables are needed to improve the model.

---

### **Task 3: Refining the Model Using Multiple Linear Regression**
- **Steps**:
  - Data Cleaning: Handled missing values, duplicates, and irrelevant columns.
  - Skewness Analysis: Applied log transformation to variables with high skewness for normality.
- **Key Results**:
  - Including Product Price as a predictor significantly improved the model.
  - Moderately high R-squared and adjusted R-squared values indicate better explanatory power.
  - Product Price was a stronger predictor (coefficient = 0.95) than Discount (coefficient = 0.07).

---

### **Task 4: Advanced Multiple Linear Regression**
- **Steps**:
  - Transformed categorical variables using dummy encoding.
  - Checked for multicollinearity using VIF analysis (all values < 5, indicating no multicollinearity).
  - Refined the model with additional variables such as Age, Gender, and Product Category.
- **Key Results**:
  - High R-squared and adjusted R-squared values indicate a well-fit model.
  - Residuals showed a random distribution around 0, further validating the model.
  - Product Price remains the most significant predictor.

---

### **Task 5: Predictive Modeling**
- Used the regression model to predict Total Amount Spent.
- **Model Performance**:
  - Predictions closely follow the 45-degree diagonal line, though deviations suggest room for improvement.
  - Further refinement with additional features or outlier handling could enhance accuracy.

---

## **Key Insights**
1. **Correlation**:
   - Discount has a limited but significant impact on Total Amount Spent.
2. **Regression**:
   - Product Price is the dominant predictor of Total Amount Spent.
   - Including multiple variables improves the model's accuracy.
3. **Advanced Modeling**:
   - Proper data cleaning and handling multicollinearity enhance model reliability.
4. **Predictive Modeling**:
   - The regression model performs well but could benefit from additional fine-tuning.

---

## **Recommendations**
1. **Focus on Product Price**: Businesses should prioritize strategies that leverage product pricing to drive sales.
2. **Optimize Discounts**: Use discounts strategically, as their impact on Total Amount Spent is relatively small.

---

## **Repository Structure**
```plaintext
Regression Analysis in Excel Project/
│
├── Link to Notes and Documentation.md          # Link to Google Docs containing detailed notes and interpretations.
├── Regression Analysis Dataset.xlsx       # Dataset used for analysis.
└── README.md                              # Project documentation (this file).
