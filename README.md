# 🚢 Titanic Classification

A beginner-friendly machine learning project predicting Titanic passenger survival using Python and Random Forest.

## 📊 Project Overview
* **Goal**: Predict passenger survival based on features like age, sex, class, and fare
* **Dataset**: Titanic dataset (train.csv, test.csv)
* **Tech Stack**: Python, Pandas, NumPy, Scikit-learn, Matplotlib
* **Model**: Random Forest Classifier

## ⚙️ Approach

### 1. **Data Preprocessing**
- Removed `Cabin` column (too many missing values)
- Filled missing `Age` values using Title-based mean imputation
- Filled missing `Fare` with mean value
- Filled missing `Embarked` with mode (most frequent value)

### 2. **Feature Engineering**
- Extracted `Title` from passenger names (Mr, Mrs, Miss, Master)
- Grouped rare titles together
- Converted categorical variables to numeric using `pd.get_dummies()`

### 3. **Modeling**
- Split data into train (891 rows) and test (418 rows)
- Trained Random Forest Classifier
- Generated predictions for Kaggle submission

## 📁 Files
```
titanic-classification/
├── ttrain.csv          # Training data
├── ttest.csv           # Test data
├── classification.ipynb # Main notebook
└── sonuc1.csv          # Predictions
```

## 🚀 Usage
```bash
# Install dependencies
pip install pandas numpy scikit-learn matplotlib

# Run the notebook
jupyter notebook classification.ipynb
```

## 📝 Key Features
✅ Title extraction from names  
✅ Smart missing value imputation  
✅ Categorical encoding  
✅ Random Forest classifier  


## 📄 License
MIT License
