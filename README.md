# Hyperparameter-Tuning-MNIST
Hyperparameter Tuning for SVC on MNIST Digits dataset

This repository demonstrates Support Vector Machine (SVM) hyperparameter tuning using GridSearchCV on the Digits dataset from sklearn.datasets. The goal is to compare a baseline model with a tuned model and observe improvements in classification performance.

Overview:
The project follows these steps:
1. Load Dataset - The Digits dataset consists of 8x8 grayscale images of handwritten digits (0-9).
2. Data Preprocessing - Standardization using StandardScaler.
3. Train-Test Split - Splitting into 80% training and 20% testing data.
4. Baseline Model - Using a default SVC() with no hyperparameter tuning.
5. Hyperparameter Tuning - Using GridSearchCV to find the best combination of:
A) C (Regularization parameter)
B) kernel (RBF or Polynomial)
C) gamma (Scale, Auto, 0.01, 0.001)
6. Evaluate Performance - Compare accuracy and classification reports before and after tuning.

Results - Accuracy:
- Baseline: 97.5 % 
- Tuned SVM: 99.4 %
- Improvement: 1.9 %

Dependencies:
- Python 3.x
- NumPy
- Pandas
- Scikit-Learn

Install Scikit-Learn dependencies using:
pip install numpy pandas scikit-learn

Running the Code:
To run the project locally:
1. Clone the repository:
- git clone https://github.com/Oliver-VG/Hyperparameter-Tuning-MNIST.git
- cd svm-hyperparameter-tuning
2. Run the Jupyter Notebook:
jupyter notebook
3. Open the notebook and execute the cell.

Key Takeaways:
- Hyperparameter tuning significantly improves SVM performance.
- GridSearchCV automates the search for the best hyperparameters.
- A well-tuned SVM can enhance classification accuracy over a baseline model.
