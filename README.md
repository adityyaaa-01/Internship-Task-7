# Support Vector Machine (SVM) Classification – Internship Task 7

## 📌 Overview
This project is part of my **AI & ML Internship** (Task 5), where I implemented **Support Vector Machines (SVM)** for binary classification using the **Breast Cancer dataset**.

The task includes:
- Training SVM with **Linear** and **RBF** kernels
- Visualizing decision boundaries (via PCA)
- Tuning hyperparameters (**C** and **gamma**)
- Evaluating the model using cross-validation

---

## 📂 Dataset
- **Name:** Breast Cancer Dataset  
- **Source:** Provided as part of the internship  
- **Target:** Diagnosis (M = Malignant, B = Benign)

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📊 Steps Performed
1. **Load and Prepare Dataset** – Removed unnecessary columns, mapped target labels to binary values.  
2. **Train/Test Split** – Used `stratify = y` to maintain class balance in both sets.  
3. **Feature Scaling** – Standardized features for better SVM performance.  
4. **SVM Training** –  
   - Linear Kernel  
   - RBF Kernel  
5. **Visualization** – Reduced features to 2D with PCA and plotted decision boundaries.  
6. **Hyperparameter Tuning** – Used `GridSearchCV` to find best `C` and `gamma` values.  
7. **Cross-Validation** – Calculated average accuracy using k-fold CV.  

---

## 📈 Results
- **Linear Kernel Accuracy:** 96.49%  
- **RBF Kernel Accuracy:** 96.49%  
- **Best Parameters (RBF):** `C = X`, `gamma = X`  
- **Best Model Accuracy:** 98.24%  
- **Average CV Accuracy:** 62.74%  

---

## 📷 Visualizations
- Decision Boundary Plot (PCA 2D projection)  
- Confusion Matrix Heatmap  

---

## 📚 Key Learnings
- Difference between **Linear** and **RBF** kernels in SVM  
- Importance of scaling features in SVM models  
- How `C` controls margin size and misclassification tolerance  
- How `gamma` affects the RBF kernel's influence  
- Role of `stratify = y` in keeping class distributions balanced  
