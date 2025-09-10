# Machine Learning Assisted Loan Approval Prediction

Final project for the **Data Science Bootcamp** by **Digica Academy**.

## Overview
This project builds and evaluates multiple machine learning model to assist in loan approval decisions for a financial institution.  
The goal is to **reduce manual processing time**, **increase operational capacity**, and **boost revenue** while maintaining strong risk management.

## Business Context
- Current manual approval takes ~2 hours per application.
- By implementing the ML model, processing time can be reduced to ~30 minutes.
- Potential capacity increase: **up to 4x more applications** with the same staff.
- Estimated revenue growth calculated based on approval rate, interest rate, and operational bottleneck removal.

## Dataset
- Source: [Kaggle - Loan Approval Prediction](https://www.kaggle.com/)
- Total records: **4,269 applications** (1-month operational data assumption)
- Features include: `cibil_score`, `loan_term`, `income_annum`, `education`, and various asset values.
- Target: Loan approval status (0 = Rejected, 1 = Approved)

## Key Findings
- **Cibil score** is the strongest factor influencing approval decisions.
- **Loan term** has a smaller but notable correlation (shorter terms are more likely to be approved).
- Other features show negligible influence on the target.

## Model Performance
- **Model**: Random Forest
- **Precision**: ~1.0 (avoids false positives)
- **Recall**: ~0.95 (small trade-off in false negatives)
- Supports **hybrid decision-making** (ML + manual review for high-risk cases).

## Business Impact
- Estimated **4x increase in processing capacity**.
- Potential revenue boost in the billions of rupees annually.
- Breakeven point: ~225 additional approved applications per month.

## Limitations & Improvements
- Model does not predict repayment likelihood yet.
- Historical data bias may affect predictions.
- Future work: integrate repayment risk data, retrain periodically, and fine-tune thresholds.

---

### Author
Erick — Final project submission for **Digica Academy** Data Science Bootcamp.
