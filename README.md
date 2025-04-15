# 🧠 Mental Health Meme Classifier - Inference Notebooks

This repository contains Jupyter notebooks for performing inference on mental health memes using pretrained models. The classification is divided into two tasks:

- `trained_anxiety.ipynb`: Classifies memes into one of several anxiety categories (single-label classification).
- `trained_depression.ipynb`: Predicts multiple subcategories of depression (multi-label classification).

Both notebooks use pretrained multimodal models that combine visual and textual meme features.

---

## 🧠 Models Overview

### 1. `trained_anxiety.ipynb`

This notebook includes:

- Data preprocessing for anxiety-related features  
- Feature extraction and vectorization  
- Model training using *[insert algorithm, e.g., Logistic Regression, SVM, or BERT]*  
- Evaluation metrics: accuracy, precision, recall, F1-score  
- Confusion matrix and visualizations  

### 2. `trained_depression.ipynb`

This notebook includes:

- Data loading and cleaning for depression detection  
- Natural language processing (if applicable)  
- Model training and hyperparameter tuning  
- Performance evaluation and metrics visualization  
- Inference on new or sample data  

---

## ⚙️ Requirements

To run the notebooks, install the following Python libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

Additional packages (if used):

```bash
pip install nltk xgboost keras tensorflow spacy transformers
```

---

## 🚀 Getting Started

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks and run cells sequentially (ensure dataset paths are correctly configured if applicable).

---

## 📊 Expected Output

Each notebook provides:

- Model performance metrics on validation/test sets  
- Confusion matrices  
- ROC curves or feature importance graphs (if applicable)  

---

## 📌 Important Notes

- These models are for **educational/research purposes only**.  
- **Not intended for clinical diagnosis or treatment decisions.**  
- Always anonymize sensitive data before processing.  

---

## 👤 Author(s)

- Manan Aggarwal (2022273)
- Shobhit Raj (2022482)
- Souparno Ghose (2022506)

---
