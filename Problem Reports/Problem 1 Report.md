### Pre-Processing
- **Why did we standardize the data?**
    - LASSO and Ridge penalize based on **magnitude of coefficients**, so **standardization prevents features with larger scales from dominating the penalty.**
- **Any missing values or outliers?**
    - Mention **if you handled missing data** or **outliers.**
- **Standardization process:
from sklearn.preprocessing import StandardScaler
scaler = StandardScaler()
X_train_scaled = scaler.fit_transform(X_train)
X_val_scaled = scaler.transform(X_val)
X_test_scaled = scaler.transform(X_test)

