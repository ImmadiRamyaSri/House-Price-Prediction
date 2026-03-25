<<<<<<< HEAD
# House Price Prediction 🏠

## About the Project
Predicting house prices using Machine Learning
based on King County, Seattle dataset.
This project was built and improved while learning
Machine Learning through Andrew Ng's ML Specialization.

## Dataset
- Source: Kaggle - House Prices King County
- 21,000+ houses
- 20 features including size, location, condition

## Project Structure
- House_Price_Basic.ipynb    → Basic Linear Regression
- House_Price_Improved.ipynb → Improved with Feature Engineering
                               and Multiple Models

## Features Used
- sqft_living, bedrooms, bathrooms
- grade, condition, view
- yr_built, floors, waterfront
- sqft_living15, lat

## Feature Engineering Applied
- house_age     → calculated from yr_built
- is_renovated  → extracted from yr_renovated
- bed_bath_rooms → bedrooms + bathrooms combined
- sqft_ratio    → sqft_living / sqft_lot

## Models Used & Results

### Basic Notebook
| Model | R2 Score | RMSE |
|---|---|---|
| Linear Regression | 0.6935 | 210,255 |

### Improved Notebook
| Model | R2 Score | RMSE |
|---|---|---|
| Linear Regression | 0.7107 | 200,961 |
| Ridge Regression | 0.7107 | 200,961 |
| Lasso Regression | 0.7107 | 200,961 |
| Polynomial Degree 2 | 0.7847 | 173,390 |
| Polynomial Degree 3 | 0.6383 | 224,717 |

✅ Best Model → Polynomial Regression Degree 2
✅ Best R2    → 0.7847
✅ Best RMSE  → 173,390

## Overall Improvement
| | R2 Score | RMSE |
|---|---|---|
| Basic Notebook | 0.6935 | 210,255 |
| Improved Notebook | 0.7847 | 173,390 |
| Improvement | +0.091 | -36,865 |

## Key Findings
- sqft_living is most important feature
- grade is second most important
- house_age (engineered feature) is 3rd most important
- Location (lat) significantly affects price
- Polynomial Degree 2 is sweet spot
- Higher degrees cause overfitting

## Scaling Comparison
- StandardScaler, RobustScaler, ColumnTransformer tested
- Linear Regression is scale invariant
- All scalers gave same R2: 0.7107

## Libraries Used
- Python
- Pandas, Numpy
- Scikit-learn
- Matplotlib, Seaborn

## Steps Followed
1. Data Loading
2. Exploratory Data Analysis
3. Data Cleaning
4. Feature Engineering
5. Feature Selection using Heatmap
6. Train Test Split
7. Feature Scaling (3 methods compared)
8. Model Building (5 models compared)
9. Model Evaluation
10. Feature Importance Analysis

## Future Improvements
- Random Forest (after Andrew Ng Course 2)
- XGBoost (after Andrew Ng Course 2)
- Target R2 → 0.85+
- Hyperparameter tuning

## Learning Journey
- Started  → R2: 0.6935 (Basic Linear Regression)
- Improved → R2: 0.7847 (Polynomial Degree 2)
- Applied concepts from Andrew Ng's ML Specialization:
  ✅ Feature Engineering
  ✅ Feature Scaling
  ✅ Regularization (Ridge & Lasso)
  ✅ Polynomial Regression
  ✅ Overfitting & Underfitting

## Author
Ramya Sri Lalitha
B.Tech Computer Science & Engineering
GitHub: github.com/ImmadiRamyaSri