Attrition Risk Early-Warning System — predictive modeling + Tableau dashboard (demo)
# Attrition Risk Early-Warning System (Demo)

**Goal:** Predict employee attrition risk and explain top drivers for HR leaders.  
**Tech stack:** Python (pandas, scikit-learn, XGBoost, SHAP), Tableau, Excel.

## Highlights
- XGBoost classifier trained on IBM HR Attrition dataset.  
- AUC = 0.82 (test set).  
- SHAP values explain top attrition drivers (overtime, pay, tenure).
- “SHAP analysis revealed that Overtime, Stock Option Level, and Monthly Income were the top drivers of attrition risk.”
- Tableau dashboard for executives: [Attrition Command Center](https://public.tableau.com/app/profile/vishnu.thogiti/viz/AttritionCommandCenterVishnuThogiti/AttritionCommandCenter).  
- Excel pivot demo for HR business partners.  

## Privacy
- Employee IDs hashed.
- Small-cell suppression applied (n < 5).
