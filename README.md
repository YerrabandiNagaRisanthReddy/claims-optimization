# Claims Settlement Optimization System

This project is an AI-powered system that recommends optimal insurance claim settlement strategies by predicting claim payout amounts and evaluating legal, financial, and customer satisfaction costs.

---

## 🧠 Problem Statement

Create a system that determines optimal claim settlement amounts considering:
- ⚖️ Legal costs
- 😊 Customer satisfaction
- 💼 Company profitability

---

## 🚀 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn (Random Forest)
- Google Colab
- Git & GitHub

---

## 🧩 Modules & Workflow

1. **Data Loading**: Ingests Medicare insurance claim dataset
2. **Preprocessing**: Encodes categorical variables, removes missing values
3. **Modeling**: Predicts claim payment amount using Random Forest Regressor
4. **Optimization**: Calculates legal costs, customer impact, and decides Settle vs Litigate
5. **Recommendation Engine**: Outputs action plan with cost-benefit breakdown

---

## 📊 Sample Output

Claim Amount: 20700.0
Claim Type: inpatient
Risk Score: 3.57
Legal Cost Estimate: 1714.0
Customer Impact Cost: 643.0
Expected Litigation Cost: 13761.53
Recommended Action: Settle
Settlement Offer: 12420.0

---

## 📦 How to Run

1. Clone the repo:
git clone https://github.com/YerrabandiNagaRisanthReddy/claims-optimization.git


2. Open the notebook in Google Colab

3. Upload the dataset files: `Inpatient_Claim.csv`, `bene_file.csv`

4. Run cells step-by-step to train model and test recommendations

---

## 🔐 Authentication

GitHub authentication used via **Personal Access Token (PAT)**

---

## ✅ Status

All implementation steps are complete — model trained, logic implemented, GitHub repository prepared.

