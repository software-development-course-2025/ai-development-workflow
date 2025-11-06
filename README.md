# Week5-AI-Development-Workflow-Assignment

AI Workflow Development – Healthcare Case Study 🧠💉

This repository contains the practical implementation and reflections for our Week 5 assignment on AI Development Workflow. It demonstrates how machine learning models can be built, evaluated, optimized, and ethically reflected on within a real-world healthcare scenario.

The content covers model development, hyperparameter tuning, critical thinking on ethics & bias, and a final workflow reflection — showing how AI moves from idea → model → deployment → continuous monitoring.

### Part 1 – Practical Model Development (Crop Yield Prediction)
- Built a Random Forest Regressor using rainfall, soil quality, sunlight hours, fertilizer and farm size.
- Achieved very strong model performance (R² ≈ 0.9983).
- **farm_size_hectares** was the most influential feature.
- Main KPI used: **Mean Absolute Error (MAE)**.

### Part 2 – Case Study Application (Hospital Readmission Prediction)
- Developed a predictive model to identify patients at risk of being readmitted within 30 days.
- Main objective: prioritize high recall so fewer high-risk patients are missed (target ≈ 75% recall).
- Model used: **Logistic Regression (L1)** for interpretability and fast clinical decision support.
- Data sources considered: EHR, SDOH (social determinants), and claims/administrative records.
- Ethical focus: reduce algorithmic bias across demographics + ensure HIPAA privacy compliance.
- Deployment concept: integrate with hospital EHR using API + generate risk score and top contributing factors.

### Part 3 – Critical Thinking (Ethics & Trade-offs)
- Discussed how biased training data can harm patient outcomes and widen health disparities.
- Proposed fairness-aware training (e.g., demographic parity constraints) to reduce bias.
- Compared simple vs complex models: interpretability is more important for healthcare adoption.
- Recommended simpler models when computational resources are limited (faster + more practical).

### Part 4 – Reflection & Workflow Diagram

#### Reflection
- Most challenging part: balancing statistical optimization with **real-world deployment constraints**.
- Reasons: changing patient demographics, ethical complexity, low trust from clinicians, and “last-mile” deployment work being heavy (APIs, docs, pipelines).
- With more time/resources: do deeper stakeholder engagement, fairness testing, active monitoring, SHAP/LIME explainability, and long-term clinical impact studies.

#### AI Development Workflow (High-level)

Problem Definition → Data Prep → Feature Engineering → Model Training → Evaluation → Deployment → Monitoring → **Iteration/Feedback loop**


---

## Contributors

| Name | GitHub |
|------|--------|
| **Stephen Ayankoso** | https://github.com/Steve-ayan |
| **Obinwa Ogechi** | https://github.com/Perpetual-Ogetec-python |
| **Onyeka Nwokike** | https://github.com/Nwokike |

---

This repository shows our ability to:
- design, train, and evaluate ML models
- apply critical thinking around ethics and deployment
- document and reflect on the AI workflow end-to-end
