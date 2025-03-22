# 💎 Diamond Naive Bayes Classifier

This project demonstrates the use of a **Bernoulli Naive Bayes classifier** to predict whether a diamond has an **Ideal cut** based on its physical characteristics.

We apply class balancing, polynomial feature expansion, and evaluate model performance with standard classification metrics.

---

## 📊 Project Objectives

- Predict **Ideal Cut** classification using:
  - Bernoulli Naive Bayes
- Handle class imbalance using **Random Undersampling**
- Extract meaningful features from physical attributes of diamonds

---

## 📁 Dataset

- **Name**: Diamonds Dataset  
- **Source**: [Kaggle – Diamonds by Shivam Bansal](https://www.kaggle.com/datasets/shivam2503/diamonds)

> Download the dataset and place it in the `data/` folder as `diamonds.csv`.

---

## 🧪 Techniques Used

- Polynomial Feature Expansion (degree = 3)
- Data Standardization (`StandardScaler`)
- Class Balancing (`RandomUnderSampler`)
- Classification with `BernoulliNB(alpha=0.8)`
- Evaluation:
  - R² Score
  - Matthews Correlation Coefficient (MCC)
  - Confusion Matrix
  - Classification Report

---

## 🧱 Project Structure

```
diamond-naive-bayes/
│
├── data/
│   └── diamonds.csv
│
├── Diamond_Naive_Bayes_Classifier.ipynb   # Full notebook
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mgedna/diamond-naive-bayes.git
   cd diamond-naive-bayes
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the dataset in `data/`:
   ```
   data/diamonds.csv
   ```

4. Launch the notebook:
   ```bash
   jupyter notebook Diamond_Naive_Bayes_Classifier.ipynb
   ```

---

## 👤 Author

**Edna Memedula** 
📫 [LinkedIn](https://www.linkedin.com/in/edna-memedula-24b519245) • [GitHub](https://github.com/mgedna) 
