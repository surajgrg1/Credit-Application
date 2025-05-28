# Credit Risk Classification Using LendingClub Data

This project applies machine learning techniques to classify loan default risk using publicly available data from **LendingClub**. The goal is to predict whether a borrower will default based on various financial, demographic, and loan-specific attributes.


## 📁 Project Structure

---

## 🔍 Objective

The primary objective is to evaluate and compare the predictive performance of **Logistic Regression** and **Decision Tree** classifiers on the loan default dataset. Key goals include:

- Predicting loan defaults based on applicant and loan features.
- Exploring trade-offs between precision, recall, and accuracy at various classification thresholds.
- Evaluating model performance on validation and test sets using standard classification metrics.

---

## 📊 Dataset

The data used in this project is derived from **LendingClub**, a peer-to-peer lending platform. The dataset includes:

- **Training set**
- **Validation set**
- **Test set**

Each entry includes borrower characteristics (e.g., income, credit history) and loan attributes (e.g., loan amount, term, interest rate), along with a binary target variable indicating default (1 = default, 0 = no default).

---

## 🛠️ Methods Used

- **Data Cleaning & Preprocessing**
- **Logistic Regression**
- **Decision Tree Classifier**
- **Threshold Tuning**
- **Confusion Matrix Analysis**
- **Evaluation Metrics:**
  - Accuracy
  - Precision
  - Recall (True Positive Rate)
  - True Negative Rate
  - False Positive Rate
  - F1 Score
  - Cost Function

---

## 📈 Key Findings

- Logistic regression performed slightly better at a threshold of **0.75**, achieving the best **F1 score and accuracy**.
- Decision trees performed well at **0.80** threshold, showing better balance in **recall and precision**.
- A trade-off exists between increasing the recall of defaults and minimizing false positives.

---

## 🧮 Tools & Libraries

- Python (v3.11)
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for optional visualizations)

---

## 📜 License

This project is for educational and academic use only. The LendingClub dataset is publicly available but should be used in accordance with their data usage guidelines.

---

## 🤝 Acknowledgments

- **LendingClub** for the dataset.
- UF AI & FinTech course materials for project inspiration and structure.
