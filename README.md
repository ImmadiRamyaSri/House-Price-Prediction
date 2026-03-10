# House Price Prediction 🏠

## About the Project
Predicting house prices using Machine Learning
based on King County, Seattle dataset.
This is my first ML project built while learning
Machine Learning.

## Dataset
- Source: Kaggle - House Prices King County
- 21,000+ houses
- 20 features including size, location, condition

## Features Used
- sqft_living, bedrooms, bathrooms
- grade, condition, view
- yr_built, floors, waterfront
- sqft_living15, lat

## Model Used
- Linear Regression
- R2 Score : 0.676
- RMSE     : 212,033

## Libraries Used
- Python
- Pandas, Numpy
- Scikit-learn
- Matplotlib, Seaborn

## Steps Followed
1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning - handled missing values
4. Feature Selection using Correlation Heatmap
5. Model Building using Linear Regression
6. Model Evaluation using R2 Score and RMSE

## Results
For a house priced at $500,000
→ Predicted sqft_living ≈ 2500 sqft

## Future Improvements
- Will try Random Forest and XGBoost
- Hyperparameter tuning
- Add more features

## Author
Ramya Sri Lalitha
B.Tech Computer Science & Engineering
```

---

**How to create this file:**

**Option 1 — Directly on GitHub (easiest):**
- Go to your repository
- Click **"Add file"** → **"Create new file"**
- Name it exactly **README.md**
- Paste the above content
- Click **"Commit changes"** ✅

**Option 2 — On your computer:**
- Open Notepad
- Paste the content
- Save as **README.md** in your project folder
- Then upload to GitHub

---

**One important thing:**

Update the R2 Score and RMSE with your **actual values** — you already have them:
```
R2 Score : 0.6761035504336752
RMSE     : 212033.77031852517