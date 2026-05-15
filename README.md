# Machine Learning-Based Water Quality Assessment for Aquaculture: A Cost-Optimized and Explainable Framework
1. Temperature
2. Turbidity
3. Dissolved Oxygen (DO)
4. Biochemical Oxygen Demand (BOD)
5. CO2
6. pH
7. Alkalinity
8. Hardness
9. Calcium
10. Ammonia
11. Nitrite
12. Phosphorus
13. H2S
14. Plankton

Selected Optimal Features:

- Temperature
- Turbidity
- DO
- H2S
- BOD
- Nitrite
- Ammonia
- CO2

---

# Machine Learning Models Evaluated

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- Artificial Neural Network (ANN)

---

# Best Model Performance

## XGBoost (Proposed)

| Metric | Value |
|---|---|
| Accuracy | 99.30% |
| Macro F1-Score | 0.9931 |
| Sensor Cost Reduction | 47.2% |
| Features Reduced | 14 → 8 |

---

# Explainable AI

SHAP (SHapley Additive exPlanations) was used to:

- Identify global feature importance
- Analyze class-wise feature contributions
- Generate instance-level explanations
- Improve transparency of predictions

Most Influential Features:
- Turbidity
- BOD
- Dissolved Oxygen (DO)
