# Purschase_prediction
# 🌳 Customer Purchase Prediction with Decision Tree Classifier

This project builds a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on their **demographic and behavioral data**. The model is trained on the **Bank Marketing dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).

---

## 📌 Project Objective

Predict if a customer will **subscribe to a term deposit** (target variable: `y`) based on features such as:

- Age
- Job
- Marital status
- Education
- Contact communication type
- Previous marketing outcomes, etc.

---

## 📦 Dataset

**Bank Marketing Dataset**  
- Source: UCI Machine Learning Repository  
- Format: CSV  
- Size: ~45,000 records  
- Target variable: `y` (yes/no - whether the client subscribed to a term deposit)

---

## 🛠️ Tools & Technologies

- Python 3.x
- Pandas & NumPy
- Scikit-learn
- Matplotlib and Seaborn (for visualization)
- Jupyter Notebook

---

## 🧠 Steps Involved

1. **Load and explore the dataset**
2. **Preprocess data**
   - Handle missing values
   - Encode categorical variables
3. **Split the dataset**
   - Train/test split
4. **Build the Decision Tree model**
5. **Evaluate model performance**
   - Accuracy, Precision, Recall, F1-score
   - Confusion matrix & visualization
6. **Interpret decision tree**
   - Feature importance

---

## 🚀 How to Run

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/customer-purchase-decision-tree.git
cd customer-purchase-decision-tree
