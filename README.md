# Breast Cancer Classification (Ensemble & SVM)

This project uses Machine Learning algorithms to classify breast tumors as either Benign or Malignant using cellular features.

## What is in this project?
- Dataset: Breast Cancer Wisconsin diagnostic dataset (569 samples, 30 features).
- Data Scaling: Standardized all features using StandardScaler.
- Models Trained & Compared:
  - Gradient Boosting Classifier
  - XGBoost Classifier (XGBClassifier)
  - Support Vector Machine with Linear Kernel (SVC(kernel='linear'))
  - Support Vector Machine with RBF Kernel (SVC(kernel='rbf'))
- Evaluation: Evaluated accuracy, precision, recall, and confusion matrix on test data.
## Results
- SVC (RBF Kernel) achieved the highest accuracy of ~99.1% on the test set.
- XGBoost & Gradient Boosting both achieved ~95.6% accuracy on the test set.
## Tools Used
- Python
- Pandas & NumPy
- Scikit-Learn
- XGBoost

## How to Run
1. Download or clone this repository.
2. Install required packages:
   `bash
   pip install pandas numpy scikit-learn xgboost

 * Open Breast_Cancer_Classification_GBM_XGB_SVM.ipynb in Jupyter Notebook or VS Code.
 * Run all cells from top to bottom.
