# AIML-TASK-5-Internship-
# Logistic Regression Classification Project

##  Project Overview
This project demonstrates a complete **Machine Learning classification workflow** using **Logistic Regression**.  
The objective is to train a model on a dataset, evaluate its performance using standard metrics, and interpret the results.

The project follows a step-by-step approach suitable for **students, beginners, and internship submissions**.

---

##  Dataset
- **File name:** `heart.csv`
- **Type:** Binary classification dataset
- **Target column:** `target`
  - `1` → Positive class
  - `0` → Negative class

---

##  Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

##  Project Workflow

### 1️ Data Loading
- Dataset is loaded using Pandas
- Basic inspection using `.head()` and `.shape()`

### 2️ Feature & Target Separation
- Features (`X`) are separated from the target variable (`y`)

### 3️ Train–Test Split
- Dataset is split into:
  - **80% Training Data**
  - **20% Testing Data**
- Purpose:
  - Training data is used to learn patterns
  - Testing data is used to evaluate model performance

### 4️ Model Training
- **Logistic Regression** is used
- Model is trained using training data

### 5️ Prediction
- Model predicts outcomes on unseen test data

### 6️⃣ Model Evaluation
The model is evaluated using:
- **Accuracy**
- **Precision**
- **Recall**

### 7️ Confusion Matrix
- Visualized using a heatmap
- Helps understand:
  - True Positives
  - True Negatives
  - False Positives
  - False Negatives

### 8️ Result Interpretation
- Accuracy shows overall correctness
- Precision measures prediction reliability
- Recall measures detection capability of positive cases
- Confusion matrix highlights error distribution

---

## Evaluation Metrics Explained

| Metric | Description |
|------|------------|
| Accuracy | Overall correctness of the model |
| Precision | Correct positive predictions |
| Recall | Ability to identify actual positives |
| Confusion Matrix | Detailed error analysis |

---

##  How to Run the Project

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/logistic-regression-project.git
