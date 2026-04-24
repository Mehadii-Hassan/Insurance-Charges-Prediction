# Insurance Charges Prediction

A machine learning project to predict insurance charges using various demographic and health factors.

## 📊 Project Overview

This project builds a Linear Regression model to predict insurance charges based on features like age, sex, BMI, number of children, smoking status, and region.

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

## 📁 Project Structure

| File | Description |
|------|-------------|
| `insurance.csv` | Dataset containing insurance customer data |
| `insurance_charge_prediction.ipynb` | Jupyter notebook with full analysis |
| `LICENSE` | Project license |

## 📈 Key Steps

1. **Exploratory Data Analysis (EDA)**
   - Data overview and structure check
   - Missing value and duplicate analysis
   - Distribution visualization

2. **Data Cleaning & Preprocessing**
   - Removed duplicate rows
   - Encoded categorical variables (sex, smoker)
   - One-hot encoding for region

3. **Feature Engineering**
   - Created BMI categories (Underweight, Normal, Overweight, Obese)
   - Applied StandardScaler to numerical features

4. **Model Training**
   - Linear Regression model
   - Train-test split (80-20)

5. **Model Evaluation**
   - MAE, MSE, RMSE metrics
   - R² Score and Adjusted R²

## 📋 Dataset Features

| Feature | Description |
|---------|-------------|
| `age` | Age of the insured person |
| `sex` | Gender (male/female) |
| `bmi` | Body Mass Index |
| `children` | Number of dependents |
| `smoker` | Smoking status (yes/no) |
| `region` | Geographic region |
| `charges` | Insurance charges (target variable) |

## 🚀 How to Run

1. Clone the repository
2. Open `insurance_charge_prediction.ipynb` in Jupyter
3. Run all cells sequentially

```bash
# Install required packages
pip install numpy pandas matplotlib seaborn scikit-learn
```

## 📊 Results

The model achieves strong predictive performance with a high R² score, explaining a significant portion of the variance in insurance charges.

---

⭐ If you found this helpful, don't forget to star the repository!