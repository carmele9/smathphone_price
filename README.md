# Smartphone Price Prediction

A machine learning project for predicting smartphone prices using data preprocessing and machine learning models.

## 📋 Overview

This project analyzes smartphone specifications and market data to build a predictive model that can estimate smartphone prices. The project includes data preprocessing, exploratory analysis, and training of machine learning models using CatBoost.

## 📁 Project Structure

```
smathphone_price/
├── data/
│   ├── smartphones.csv              # Raw smartphone dataset
│   └── smartphones_cleaned.csv      # Cleaned and preprocessed dataset
├── preprocessing/
│   └── preprocessing.ipynb          # Data cleaning and preprocessing notebook
├── training/
│   ├── price_predicition.ipynb      # Model training and evaluation notebook
│   └── catboost_info/               # CatBoost training logs and information
└── README.md                        # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- pandas
- scikit-learn
- catboost
- numpy
- matplotlib/seaborn (for visualization)

### Installation

```bash
# Clone the repository
git clone https://github.com/carmele9/smathphone_price.git
cd smathphone_price

# Install required packages
pip install jupyter pandas scikit-learn catboost numpy matplotlib seaborn
```

## 📊 Dataset

The project uses smartphone data with the following pipeline:

1. **Raw Data** (`data/smartphones.csv`)
   - Contains raw smartphone specifications and pricing information

2. **Cleaned Data** (`data/smartphones_cleaned.csv`)
   - Processed dataset with handled missing values and normalized features
   - Ready for model training

## 📖 Workflow

### 1. Data Preprocessing
Start with `preprocessing/preprocessing.ipynb`:
- Load and explore the raw dataset
- Handle missing values
- Feature engineering and data cleaning
- Output cleaned dataset for model training

### 2. Model Training
Continue with `training/price_predicition.ipynb`:
- Load the cleaned dataset
- Perform exploratory data analysis
- Train a CatBoost model for price prediction
- Evaluate model performance
- Generate training logs in `training/catboost_info/`

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning utilities
- **CatBoost**: Gradient boosting framework for price prediction
- **Jupyter Notebook**: Interactive development environment

## 📈 Model

The project uses **CatBoost** (Categorical Boosting), a gradient boosting framework that:
- Handles categorical features efficiently
- Provides robust predictions
- Generates detailed training logs for analysis

## 💡 Usage

1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Run the notebooks in order:
   - First: `preprocessing/preprocessing.ipynb`
   - Second: `training/price_predicition.ipynb`

3. The trained model and predictions will be available after running the training notebook

## 📝 Notes

- Ensure you run the preprocessing notebook before the training notebook
- The training process generates logs in the `training/catboost_info/` directory
- Model performance metrics and visualizations are included in the training notebook

## 📄 License

This project is open source and available for educational and research purposes.

## 👨‍💻 Author

[carmele9](https://github.com/carmele9)

---

**Last Updated**: 2026-06-04
