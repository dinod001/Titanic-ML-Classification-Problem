# Machine Learning Model Comparison

## 📌 Introduction
This project focuses on comparing different machine learning models, including Logistic Regression (plain, L1, L2) and ensemble methods (Bagging, Boosting, CatBoost).  
Both **from-scratch implementations** and **library-based implementations** were tested.  
The models were evaluated using metrics such as **Accuracy, F1 Score, and AUC** to identify the best-performing approaches.

---

## 🚀 Features
- Implemented Logistic Regression (without regularization, L1, L2)
- Implemented Bagging and Boosting from scratch
- Used library implementations for comparison (Scikit-learn, CatBoost)
- Preprocessing pipeline: handling missing values, one-hot encoding, scaling
- Model evaluation with multiple performance metrics
- Performance comparison table and analysis

---

## 🛠️ Technologies Used
- Python 3.11.13  
- Pandas, NumPy  
- Scikit-learn   
- Matplotlib,seaborn (for visualization)

---

## 📂 Project Structure

├── artifacts/ # Saved preprocessed numpy arrays
│ ├── X_train.npz
│ ├── X_test.npz
│ ├── Y_train.npz
│ ├── Y_test.npz
│
├── B_from_scratch_models/ # Custom from-scratch models
│ ├── L1 Regularised Logistic Regression.ipynb
│ ├── L2 Regularised Logistic Regression.ipynb
│ ├── Simple Logistic Regression.ipynb
│ ├── Simple Bagging decision tree.ipynb
│ ├── Simple Boosting decision tree.ipynb
│
├── data/ # Dataset files
│ ├── raw/
│ │ └── Titanic-Dataset.csv
│ ├── processed/
│ └── titanicDataset_Final.csv
│
├── Section C - Library Implementations/ # Scikit-learn & CatBoost
│ ├── A_minimal_prep_and_split.ipynb
│ ├── C_library_models.ipynb
│ ├── catboost_info/
├
├── requirments.txt

## Install Dependecies

pip install -r requirements.txt

