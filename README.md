# Rock vs Mine Classification using Logistic Regression

This project applies a simple yet effective machine learning approach — **logistic regression** — to classify sonar signal returns as either **rock** or **mine**. It demonstrates a full pipeline from data loading to model evaluation using the [Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks)).

---

## 📁 Dataset

- **Source**: [UCI ML Repository – Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- **Instances**: 208
- **Features**: 60 numerical values per instance representing sonar energy at various frequencies
- **Labels**:
  - `M` — Mine
  - `R` — Rock

---

##  ML Pipeline

- Load and explore dataset
- Preprocess and normalize features
- Encode labels (`M` → 1, `R` → 0)
- Split data into training and test sets
- Train a **Logistic Regression** model
- Evaluate with:
  - Accuracy score

---

## 🛠 Tech Stack

- Python 3
- NumPy & Pandas
- scikit-learn
- Matplotlib / Seaborn

---
