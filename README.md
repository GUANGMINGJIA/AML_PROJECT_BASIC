# AML_PROJECT_BASIC
**Basic Logistic Regression on Breast Cancer Wisconsin Dataset**
# **Breast Cancer Benign vs Malignant Diagnosis: Logistic Regression Analysis (Binary Classification)**
I selected the `BASIC - 2 Breast Cancer Wisconsin (Diagnostic)` dataset from the `Suggested Datasets` document as my **AML-BASIC project**.  
In this dataset, there are **569** samples in total, and each sample contains **30** nuclear features (e.g., radius, texture). The data is derived from fine needle aspiration biopsies (FNA biopsies).

**In this project, I will address the following challenges:**  
Feature engineering for related indicators (mean values, standard errors, extreme values, etc.).  
Handling class imbalance (357 benign samples vs. 212 malignant samples).  

**Additionally**    
Based on the first submitted version and your feedback, I have added a complete workflow covering ***hypothesis, data exploration, baseline comparison, model building, and result interpretation***.     
The report format is also optimized by combining `Markdown cells` with executable code blocks for better readability.

**Based on your email feedback, this version mainly improves the following aspects:**
## 1. Added Baseline

Introduced a `DummyClassifier` as a baseline model to provide a clear benchmark for evaluating the logistic regression results **(accuracy ~ 63% vs ~97%)**.

## 2. Improved EDA and Data Processing

Enhanced the EDA by visualizing distributions, label imbalance, and correlation heatmaps.  
Added automated removal of highly correlated features (corr > 0.9) to **reduce multicollinearity risks and make the dataset cleaner**.

## 3. Improved Presentation Format

Replaced plain text explanations with a clear Markdown + Code + Explain structure, **making the notebook more readable and modular**.

## 4. Improved Result Analysis \& Extended Discussion

Added a final discussion section covering limitations, potential risks, and ideas for extending the pipeline.  
This lays a foundation for further improvements in AML-Advanced projects.

### 4.1 Other improvements or reservations:

More Appropriate Class Imbalance Handling  
Stricter Feature Standardization Steps  
More Comprehensive Performance Metrics
