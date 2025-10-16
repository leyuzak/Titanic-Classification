# 🚢 Titanic Classification

This project predicts whether a passenger survived the Titanic disaster using machine learning.  
It demonstrates data preprocessing, exploratory data analysis (EDA), and model building with Python.

## 📊 Project Overview

- **Goal:** Predict passenger survival based on features such as age, sex, ticket class, and fare.  
- **Dataset:** Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic).  
- **Tech Stack:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.  
- **Models Used:** Logistic Regression, Random Forest, and XGBoost.

## ⚙️ Steps

1. Data cleaning and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering  
4. Model training and evaluation  
5. Prediction on test data

## 🚀 Results

Achieved around **80% accuracy** on the test set.

## 📁 Project Structure
```
titanic-classification/
├── 📁 data/
│   ├── raw/
│   │   ├── train.csv
│   │   └── test.csv
│   └── processed/
│       ├── train_processed.csv
│       └── test_processed.csv
├── 📁 notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_modeling.ipynb
├── 📁 src/
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   └── model.py
├── 📁 models/
│   ├── logistic_regression.pkl
│   ├── random_forest.pkl
│   └── xgboost.pkl
├── 📄 requirements.txt
└── 📄 README.md
```

## 🛠️ Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/titanic-classification.git
cd titanic-classification

# Install required packages
pip install -r requirements.txt
```

## 🚀 Usage
```python
# Run the main script
python src/model.py

# Or explore the notebooks
jupyter notebook notebooks/01_eda.ipynb
```

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 78% | 0.76 | 0.72 | 0.74 |
| Random Forest | 80% | 0.79 | 0.77 | 0.78 |
| XGBoost | 81% | 0.80 | 0.78 | 0.79 |

## 📝 Key Features

- Age imputation using median values
- Feature engineering (family size, title extraction)
- Handling missing values in Cabin and Embarked
- One-hot encoding for categorical variables
- Feature scaling for numerical variables

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Kaggle for providing the dataset
- The data science community for inspiration and resources
