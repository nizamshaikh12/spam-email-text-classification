# Spam Email Text Classification

Binary text classification lab that builds a spam vs ham classifier on a Kaggle spam email dataset. The notebook downloads the dataset, cleans the raw email text and trains a simple machine learning model to distinguish spam from non‑spam messages.

## Project Overview

This notebook focuses on:

- Downloading a spam email dataset using Kaggle tools
- Cleaning and normalising subject/body text into a `clean_text` feature
- Preparing labels (spam vs ham)
- Training a baseline classifier on the processed text
- Evaluating model performance using standard classification metrics

The project is intended as an introductory NLP and text classification exercise.

## Data

- Kaggle spam email dataset
- Example columns:
  - `text` – raw email text
  - `spam` – binary label (1 = spam, 0 = not spam)
  - `clean_text` – cleaned and tokenised version of the email text

(See the notebook for the exact dataset link and loading steps.)

## Notebook

- `spam-email-classification-lab.ipynb`

Includes:

- Dataset download and loading
- Text cleaning pipeline
- Train/test split
- Model training and evaluation

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- scikit‑learn

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/nizamshaikh12/spam-email-text-classification.git
   cd spam-email-text-classification
   ```
2. Install dependencies (for example in a virtual environment):
   ```bash
   pip install pandas scikit-learn jupyter kagglehub
   ```
3. Ensure access to the Kaggle dataset (API or manual download) and adjust any paths in the notebook if needed.
4. Launch Jupyter and open the notebook:
   ```bash
   jupyter notebook spam-email-classification-lab.ipynb
   ```
5. Run the cells in order to reproduce the results.
