# 🚢 Titanic Survival Prediction - Kaggle Competition

[![Kaggle](https://img.shields.io/badge/Kaggle-Competition-blue)](https://www.kaggle.com/c/titanic)
[![Python](https://img.shields.io/badge/Python-3.8+-green)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org)

## 📊 **Business Analysis & Strategic Insights**

**For comprehensive business analysis and strategic insights, please check out our detailed presentation:**

### 📈 [**Predicting Survival: Machine Learning Insights from the Titanic Disaster.pptx**](./Predicting%20Survival-%20Machine%20Learning%20Insights%20from%20the%20Titanic%20Disaster.pptx)

This presentation provides:
- **Executive Summary** of key findings
- **Business implications** and real-world applications
- **Data-driven insights** for decision making

*Click the link above to download and view the full business analysis!*

## 🎯 Project Overview

This machine learning project analyzes the famous Titanic dataset to predict passenger survival using various classification algorithms. The project combines technical ML implementation with business intelligence to extract actionable insights from historical disaster data.

**Key Objectives:**
- Predict passenger survival with high accuracy
- Identify key factors influencing survival rates
- Compare multiple ML algorithms for optimal performance

## 🏆 Results

- **Best Model**: Gradient Boosting Classifier
- **Accuracy**: 79.3%
- **Kaggle Score**: 0.73
- **Key Insight**: Passenger class, gender, and age were the strongest survival predictors

## 📁 Project Structure

```
titanic-kaggle-challenge/
│
├── data/                          # Dataset files
│   ├── train.csv                  # Training data (891 passengers)
│   ├── test.csv                   # Test data for predictions
│   └── gender_submission.csv      # Sample submission format
│
├── notebooks/                     # Jupyter notebooks
│   ├── Titanic all ML Models - Top 5.ipynb    # Main analysis notebook
│   └── titanic_champion_submission.csv        
├── Predicting Survival- Machine Learning Insights from the Titanic Disaster.pptx
│                                 # 📊 Business Analysis Presentation
│
└── README.md                     # Project documentation
```

## 📊 Data Description

The Titanic dataset contains information about passengers aboard the RMS Titanic, which sank on April 15, 1912. 

**Key Features:**
- **PassengerId**: Unique identifier
- **Survived**: Target variable (0 = No, 1 = Yes)
- **Pclass**: Passenger class (1st, 2nd, 3rd)
- **Name**: Passenger name
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 🔬 Methodology

**Machine Learning Pipeline:**
1. **Data Exploration & Visualization**
2. **Feature Engineering** (handling missing values, creating new features)
3. **Model Training** with multiple algorithms:
   - Logistic Regression
   - Random Forest
   - Gradient Boosting
   - Support Vector Machine
   - Neural Networks
4. **Model Evaluation** and hyperparameter tuning
5. **Ensemble Methods** for improved performance

## 🔍 Key Findings

- **Gender Impact**: Women had a 74% survival rate vs 19% for men
- **Class Matters**: 1st class passengers had 63% survival rate vs 24% for 3rd class
- **Age Factor**: Children under 10 had higher survival rates
- **Family Size**: Small families (2-4 members) had better survival odds
- **Fare Correlation**: Higher fares correlated with better survival chances

## 🚀 Getting Started

### Prerequisites
```bash
# Create conda environment
conda create -n titanic python=3.8
conda activate titanic

# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Installation & Setup
```bash
# Clone or download this repository
cd titanic-kaggle-challenge

# Activate environment
conda activate titanic

# Launch Jupyter Notebook
jupyter notebook
```

## 💻 Usage

1. **Open the main notebook**: `notebooks/Titanic all ML Models - Top 5.ipynb`
2. **Run all cells** to reproduce the analysis
3. **View results** and model comparisons
4. **Check submissions folder** for Kaggle submission files
5. **Review the PowerPoint presentation** for business insights