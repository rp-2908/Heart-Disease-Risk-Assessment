# Heart Disease Risk Assessment 🩺
**A Predictive Classification Model achieving 95.5% accuracy using Distance-Weighted kNN.**

### 📊 Project Overview
This project focuses on the healthcare domain, specifically predicting the presence of heart disease based on patient clinical indicators. It demonstrates a full Machine Learning pipeline—from handling missing data to feature importance analysis and model fine-tuning.

### 🛠️ Technical Stack
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib
* **Environment:** Jupyter Notebook

### ⚙️ Machine Learning Pipeline
1. **Robust Preprocessing:** * Handled missing clinical data through statistical imputation.
   * Utilized **StandardScaler** to normalize features like Age and Cholesterol for distance-based calculations.
2. **Feature Engineering:**
   * Calculated **Mutual Information (MI)** scores to prioritize the most impactful indicators (e.g., Chest Pain Type, Exercise Induced Angina).
3. **Model Selection:**
   * Developed a **k-Nearest Neighbors (kNN)** classifier.
   * Optimized the model with **k=26** and **distance-weighting** to maximize predictive reliability.

### 📈 Results
* **Final Accuracy:** 95.5%
* **Key Finding:** Chest Pain Type and Exercise Induced Angina showed the highest correlation with positive heart disease risk.

### 🚀 Getting Started
1. Clone the repository: `git clone https://github.com/rp-2908/Heart-Disease-Risk-Assessment.git`
2. Install requirements: `pip install pandas scikit-learn matplotlib`
3. Open `notebooks/AIMLinoassign.ipynb` to view the analysis.
