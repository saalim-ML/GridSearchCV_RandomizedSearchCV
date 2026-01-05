# GridSearchCV_RandomizedSearchCV
 This project demonstrates "machine learning model selection and hyperparameter tuning" using **GridSearchCV** and **RandomizedSearchCV**.   The goal is to find the best-performing model by systematically searching for optimal hyperparameters using 'cross-validation'


## 📌 Key Concepts Covered

- Machine Learning Model Selection  
- Hyperparameter Tuning  
- Cross-Validation (CV = 5)  
- GridSearchCV  
- RandomizedSearchCV  
- Support Vector Machine (SVM)  
- Model Evaluation using Accuracy

- 
## 📊 Dataset Used

- **Dataset:** Breast Cancer Wisconsin Dataset  
- **Source:** `sklearn.datasets.load_breast_cancer`  
- **Type:** Binary Classification  
- **Target:**  
  - `0` → Malignant  
  - `1` → Benign  

---

## 🧠 Model Used

### Support Vector Classifier (SVC)

Hyperparameters tuned:
- `C` → Regularization parameter  
- `kernel` → `linear`, `poly`, `rbf`, `sigmoid`  

---

## 🔍 Hyperparameter Tuning Techniques

### 1️⃣ GridSearchCV
- Exhaustively searches all parameter combinations
- More accurate but computationally expensive

**Best Parameters Found:**
```python
{'C': 10, 'kernel': 'linear'}
