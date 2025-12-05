# 📨 Spam / Ham SMS Classifier (ML Project)

This is a simple **machine learning project** that classifies text messages as **spam** or **ham** (not spam) using **TF-IDF** features and a **Naive Bayes** classifier.

The goal of this project is to **demonstrate a clean ML pipeline** that is easy to explain in interviews:
- Data loading
- Basic preprocessing
- Train–test split
- Feature extraction using TF-IDF
- Model training (Multinomial Naive Bayes)
- Evaluation using precision, recall, F1-score
- Simple interactive prediction

---

## 🚀 Tech Stack

- **Language:** Python 3.x  
- **Libraries:**
  - `pandas`
  - `scikit-learn`

---

## 📂 Project Structure

```text
spam-classifier/
├─ spam_classifier.py         # main script
├─ spam_classifier.ipynb      # (optional) notebook version
├─ requirements.txt           # dependencies
├─ README.md                  # project documentation
└─ data/
   └─ spam.csv                # dataset (not committed if from Kaggle)
