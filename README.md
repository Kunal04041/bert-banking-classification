# BERT-Based Banking Text Classification

A transformer-based NLP project that uses BERT to classify banking-related queries based on the **Bank FAQ Dataset** from Kaggle. This project demonstrates fine-tuning a pre-trained BERT model for domain-specific intent classification.

---

## Project Goals

- Fine-tune BERT on real-world banking FAQs
- Classify queries into relevant banking categories (e.g., card, loan, internet banking)
- Evaluate model performance using classification metrics
- Prepare for deployment (as future enhancement)

---

## Dataset

- **Dataset Name**: [Bank FAQ Dataset]
- **Source**: Kaggle
- **Description**: A collection of frequently asked questions from the banking domain labeled into 10 categories like ‘Credit card’, ‘Loans’, ‘Accounts’, etc.
- **Format**: CSV file with `Question` and `Category` columns

| Question                              | Category      |
|---------------------------------------|---------------|
| How to apply for a debit card?        | Debit Card    |
| What is the eligibility for a loan?   | Loans         |
| I forgot my net banking password.     | Internet Bank |

---

##  Tech Stack

- Python 3.x
- Hugging Face Transformers
- TensorFlow
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

