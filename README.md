# Customer Spending Prediction using Linear Regression

This project uses **Linear Regression** to predict a customer’s **Yearly Amount Spent** based on various features like session length, app usage, and website activity.

## 📊 Dataset

The dataset includes the following features:
- `Avg. Session Length`
- `Time on App`
- `Time on Website`
- `Length of Membership`
- `Yearly Amount Spent` (Target variable)

## 📌 Objective

To build a regression model that predicts how much a customer is likely to spend yearly, using their usage behavior on a platform.

## 🧪 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## 🧱 Steps Followed

1. **Data Loading & Exploration**
   - Used `pandas` and `seaborn` for data inspection and visualization.
   - `sns.pairplot()` and `sns.heatmap()` for understanding feature relationships.

2. **Feature Selection**
   - Chose features like `Avg. Session Length`, `Time on App`, and `Time on Website`.

3. **Model Training**
   ```python
   from sklearn.linear_model import LinearRegression
   lm = LinearRegression()
   lm.fit(X_train, y_train)
