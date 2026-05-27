# 📱 Cellphone Price Prediction using Linear Regression

## 📌 Project Overview
This project predicts **cellphone prices** based on features such as RAM, weight, resolution, CPU frequency, internal memory, battery, and thickness.  
Data preprocessing includes **outlier handling with Winsorization**, feature exploration, and visualization.  
The main objective is to evaluate the relationship between **RAM** and **Price** using **Linear Regression**.

---

## 🛠️ Steps Involved

1. **Data Import**
   - Loaded dataset: `Cellphone.csv`
   - Used Pandas for initial exploration (`head()`, `tail()`, `describe()`, `info()`)

2. **Exploratory Data Analysis**
   - Listed all columns  
   - Visualized distributions and outliers using **Boxplots**

3. **Outlier Handling**
   - Applied **Winsorization** (20% limits) on selected numerical columns:  
     `weight, Price, Sale, resolution, ppi, cpu freq, internal mem, battery, thickness`

4. **Model Training**
   - Selected **RAM** as predictor variable (`X`)  
   - Target variable: **Price** (`y`)  
   - Split dataset into training and testing sets (80/20 split)  
   - Trained **Linear Regression** model using Scikit‑learn  

5. **Model Evaluation**
   - Metrics used:  
     - Mean Absolute Error (MAE): `222.73`  
     - Mean Squared Error (MSE): `74607.26`  
     - R² Score: `0.68`  

6. **Visualization**
   - Plotted **RAM vs Price** for training and testing sets  

---

## 📊 Results

| Metric | Value |
|--------|-------|
| Mean Absolute Error | 222.73 |
| Mean Squared Error  | 74607.26 |
| R² Score            | 0.68 |

- The model explains ~68% of the variance in cellphone prices using RAM as the predictor.  
- Outlier handling improved stability of predictions.  

---

## 📸 Visualizations
- Boxplots for outlier detection  
- RAM vs Price plots (Training & Testing sets)  

---

## 🛠️ Tools & Libraries Used
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit‑learn  
- SciPy  

---

## ✅ Conclusion
- **Linear Regression** shows a moderate correlation between RAM and Price.  
- Outlier handling and preprocessing improved model accuracy.  
- Further improvements can be achieved by including more features (battery, resolution, CPU frequency, etc.) and applying advanced regression techniques.  

---

## 🚀 Future Improvements
- Feature Engineering with multiple predictors  
- Hyperparameter tuning  
- Polynomial Regression / Regularization (Ridge, Lasso)  
- Deployment using Flask or Streamlit  

---

## 📌 Author
**Developed by Dhanushya**  
Passionate about **AI, Machine Learning, and Data Science Projects 🚀**
