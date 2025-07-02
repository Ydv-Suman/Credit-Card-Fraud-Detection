# 📊 Credit Card Fraud Detection

This project focuses on detecting fraudulent transactions using machine learning techniques. It is implemented in Python using a Jupyter Notebook (`Main.ipynb`) and leverages tools for preprocessing, modeling, evaluation, and hyperparameter tuning. The goal is to accurately classify rare fraudulent transactions from a large set of legitimate ones.

---

## 📁 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Transactions**: 284,807  
- **Fraud Cases**: ~0.17% (highly imbalanced)  
- **Features**:
  - `Time`, `Amount`
  - Anonymized principal components: `V1` to `V28`
  - `Class`: Target label (0 = Non-Fraud, 1 = Fraud)

---

## 🛠 Technologies Used

- **Language**: Python 3.x  
- **Notebook**: Jupyter Notebook  
- **Libraries**:
  - Data: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - ML: `scikit-learn` (`RandomForestClassifier`, `GridSearchCV`)

---

## 💻 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection

# (Optional) Create a virtual environment
conda create -n fraud-detection python=3.10
conda activate fraud-detection

# Install required packages
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook Main.ipynb

📈 Model Evaluation
The model is evaluated using:

✅ Accuracy Score

🧮 Confusion Matrix

🎯 Precision, Recall, and F1 Score

📊 ROC-AUC Curve