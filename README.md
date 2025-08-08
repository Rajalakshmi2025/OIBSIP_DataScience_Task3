#  Car Price Prediction Using Machine Learning

## Objective
To build a machine learning model that accurately predicts the selling price of a used car using various features like year, driven kilometers, fuel type, etc.

---

##  Dataset
- Dataset Name: car data.csv
- Records: 301
- Features: Car Name, Year, Present Price, Selling Price, Fuel Type, Transmission, Owner, etc.

---

##  Tools and Libraries
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (Linear Regression, Random Forest, LabelEncoder)
- Jupyter Notebook

---

##  Workflow
1. **Data Cleaning** – Checked for missing values and duplicates
2. **EDA** – Distribution plots and boxplots for feature insight
3. **Preprocessing** – Label encoding for categorical data
4. **Model Building** – Trained Linear Regression and Random Forest Regressor
5. **Model Evaluation** – Compared R², MAE, RMSE
6. **Visualization** – Actual vs Predicted, Feature Importance

---

## Model Performance

| Model | R² Score | MAE | RMSE |
|-------|----------|-----|------|
| Linear Regression | 0.75 | 1.53 | 2.55 |
| Random Forest | 0.58 | 1.40 | 3.30 |

---

##  Visualizations
- Distribution of Selling Price
- Boxplot by Fuel Type
- Scatter plots for predicted vs actual
- Feature Importance bar chart

---

##   Insights
- Petrol cars generally have lower resale value than diesel
- Older cars have much lower predicted selling prices
- Present Price is the most influential feature

---


## 🧑‍💻 Author
**Rajalakshmi V R**

---

