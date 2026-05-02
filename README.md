# 📊 Linear Regression – Student Performance Prediction

## 📌 Objective
Build a linear regression model to predict student performance based on study habits and related features.

---

## 📂 Dataset
**Features:**
- Hours Studied
- Previous Scores
- Extracurricular Activities
- Sleep Hours
- Sample Question Papers Practiced

**Target:**
- Performance Index

---

## ⚙️ Approach

1. Data preprocessing  
   - Handled categorical variable using one-hot encoding  
2. Train-test split (80/20)  
3. Model training using Linear Regression  
4. Evaluation using:
   - R² Score
   - RMSE  
5. Model diagnostics:
   - Actual vs Predicted plot  
   - Residual plot  

---

## 📈 Results

| Metric     | Value  |
|------------|--------|
| Train R²   | 0.9887 |
| Test R²    | 0.9890 |
| Train RMSE | 2.04   |
| Test RMSE  | 2.02   |

---

## 📊 Visualizations

### Actual vs Predicted
- Strong linear alignment
- Indicates excellent model fit

### Residual Plot
- Random scatter around zero
- Confirms:
  - Linearity
  - Homoscedasticity

---

## 🧠 Model Interpretation

- **Hours Studied** → strongest positive impact  
- **Previous Scores** → strong predictor  
- **Sleep Hours** → moderate positive effect  
- **Practice Papers** → small positive effect  
- **Extracurricular Activities** → minor influence  

---

## 🚀 How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt