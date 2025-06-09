# Data Science & LLM Technical Assessment — Final Report

## Approach

- Performed data cleaning, EDA, and feature engineering on structured hospital data.
- Built and evaluated classification models (Logistic Regression, Random Forest) to predict 30-day readmission.
- Used SpaCy and a HuggingFace NER model to extract medical entities from discharge notes.

## Key Results

- Random Forest ROC AUC: ~0.5, F1 (positive): ~0.35.
- Most important features: age, length of stay, number of previous admissions.
- NLP models extracted entities like medications, procedures, and diagnoses.

## Practical Implications

- More data, richer features (especially from text), and model tuning would likely improve results.
- NER can automate structuring discharge notes, but needs careful validation for clinical use.

## Next Steps

- Engineer additional features (especially from free-text notes).
- Try hyperparameter tuning and ensemble models.
- Fine-tune or use more domain-specific NLP/LLM models for entity extraction.
