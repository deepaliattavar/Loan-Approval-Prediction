# Loan-Approval-Prediction
Built a supervised machine learning pipeline to predict whether a loan application will be approved using real-world applicant data. Applied PCA to reduce dimensionality while maintaining model performance and improving interpretability for faster decision-making.  
**Result:** ~98% accuracy • **PCA:** ~55% feature reduction with ~95% variance retained. 

---

## Project Overview
Loan approval decisions are often time-consuming and prone to manual bias. This project uses a classification model to predict loan approval outcomes using applicant-level features, helping financial institutions make faster and more consistent decisions.

---

## Objective
- Clean and preprocess applicant data
- Engineer meaningful features for classification
- Reduce feature space using PCA (retain ~95% variance)
- Train and evaluate supervised ML models
- Compare performance with and without PCA

---

## Approach
1. **Data Cleaning & Preprocessing**
   - Handle missing values and inconsistent formats
   - Encode categorical variables
   - Scale/normalize features as needed

2. **Feature Engineering**
   - Create/transform variables to improve signal
   - Prepare final modeling dataset

3. **Dimensionality Reduction (PCA)**
   - Apply PCA to reduce dimensionality
   - Retain ~95% explained variance while reducing features (~55%)

4. **Model Training & Evaluation**
   - Train classification model(s)
   - Evaluate using metrics such as Accuracy, Precision, Recall, F1-score, Confusion Matrix

---

## Key Results
- Achieved **~98% accuracy** on loan approval prediction
- Reduced feature space by **~55%** with PCA while retaining **~95% variance**
- Improved training efficiency and reduced model complexity

---

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, matplotlib/seaborn
- **Notebook:** Jupyter Notebook

---

## 📂 Repository Structure
