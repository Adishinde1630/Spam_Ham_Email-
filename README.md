# Spam vs Ham Email Classifier

This repository contains a machine learning project to detect spam vs ham (non-spam) emails. It includes dataset preprocessing, feature extraction, model training, evaluation, and utilities for inference.

## Project Structure

- `spamham (1).ipynb` — Jupyter notebook with data exploration and model pipeline (main work).
- `README.md` — Project summary and usage instructions.
- `requirements.txt` — Python dependencies.

## Quick Start

1. Create a virtual environment (recommended):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Open the notebook:

```powershell
jupyter notebook "spamham (1).ipynb"
```

## Typical Workflow

- Load and clean the email dataset.
- Preprocess text (tokenization, stopword removal, stemming/lemmatization).
- Convert text to numeric features (TF-IDF, CountVectorizer, or embeddings).
- Train classification models (e.g., Logistic Regression, Random Forest, SVM).
- Evaluate using accuracy, precision, recall, F1-score, and confusion matrix.

