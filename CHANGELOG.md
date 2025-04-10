
# 📘 CHANGELOG

## [v2.1.0] - 2025-04-10

### Improved
- ✅ Retrained Logistic Regression with `class_weight='balanced'` to improve performance on minority class (`Critical`)
- ✅ Added `zero_division=0` to suppress undefined metric warnings in classification report
- 🧼 Smoothed output and clarified model performance evaluation for real-world imbalanced data
- 📉 Planned updated visualizations of new model performance on noisy, imbalanced data

---

## [v2.0.0] - 2025-04-10

### Added
- Introduced **realistic class imbalance**: 60% Ready, 25% Delayed, 15% Critical
- Injected **missing values (~10%)** in key features: `supply_delay_days`, `equipment_status_score`, `personnel_available`
- Applied **Gaussian noise** to `equipment_status_score` and `personnel_available` for real-world variability
- Clipped `equipment_status_score` to stay within 0–1 operational range

### Updated
- Prepared new dataset: `mission_readiness_data_realistic.csv`
- Planned preprocessing updates for missing data handling and model retraining
- Outlined performance comparison vs original dataset

---

## [v1.0.0] - Initial Release
- Created clean synthetic dataset
- Trained Random Forest & Logistic Regression models
- Built performance comparison chart
- Visualized feature importance
- Shared via GitHub with full README + visuals
