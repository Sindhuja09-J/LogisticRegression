### Logistic Regression - Breast Cancer Classification

**Objective:**
The goal of this project is to build a binary classification model using Logistic Regression to predict whether a tumor is malignant (1) or benign (0).

**Dataset:**
- **Dataset:** Breast Cancer Wisconsin (Diagnostic)
- **Target Column:** `diagnosis`
  - `M` → Malignant (1)
  - `B` → Benign (0)

**Tools and Libraries:**
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

**Steps Taken:**
1. **Load and Clean the Data:** 
   - Import the dataset and handle any missing values or inconsistencies.
   
2. **Convert Labels:**
   - Map the target column (`diagnosis`) to binary labels: `M` → 1 (Malignant) and `B` → 0 (Benign).

3. **Data Splitting:**
   - Split the data into training and testing sets to evaluate the model's performance.

4. **Feature Standardization:**
   - Standardize the features to ensure that all variables are on the same scale.

5. **Model Training:**
   - Train a Logistic Regression model on the training data.

6. **Model Evaluation:**
   - Evaluate the model performance using:
     - **Confusion Matrix**
     - **Precision and Recall**
     - **ROC-AUC Score**

7. **Visualization:**
   - Plot:
     - **ROC Curve** to assess the model's classification ability.
     - **Sigmoid Function** to visualize the probability mapping of predictions.
   
8. **Threshold Adjustment:**
   - Adjust the decision threshold (e.g., 0.6) to optimize model performance for specific metrics.
