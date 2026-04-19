# Codveda Data Analytics Internship

End-to-end data analytics and machine learning projects 
completed during the Codveda Data Science internship.

## Project Overview

| Level | Task | Dataset | Key Result |
|-------|------|---------|------------|
| Level 1 | Data Cleaning | Iris | Removed duplicates, imputed missing values |
| Level 1 | EDA | Iris | Petal features show 0.96 correlation |
| Level 1 | Visualization | Iris | Bar, line, scatter plots |
| Level 2 | Regression | Boston Housing | R²=0.669, RMSE=$4.93k |
| Level 2 | K-Means Clustering | Iris | 83.7% accuracy, rediscovered species |
| Level 3 | Classification | Customer Churn | 95.2% accuracy, 100% precision |
| Level 3 | NLP Sentiment | Social Media | TextBlob pipeline, 46.7% agreement |

## Key Results

### Churn Classification (Level 3 Task 1)
- Trained Decision Tree, Logistic Regression, Random Forest
- Tuned Random Forest with GridSearchCV (135 model fits)
- Achieved **100% precision** and **95.2% accuracy**
- Zero false positives on 667 test customers

### K-Means Clustering (Level 2 Task 3)
- Discovered 3 species clusters WITHOUT using labels
- **83.7% overall accuracy** matching botanical classifications
- Setosa identified with **100% perfect accuracy**
- Adjusted Rand Score: 0.6202

### Linear Regression (Level 2 Task 1)
- Predicted Boston house prices from 13 features
- R² = 0.669 (explains 66.9% of price variation)
- RMSE = $4.93k average prediction error
- Identified LSTAT and RM as strongest predictors

## Tech Stack

```
Python 3.x
pandas          — data manipulation
numpy           — numerical operations
matplotlib      — data visualization
seaborn         — statistical visualization
scikit-learn    — machine learning
textblob        — NLP sentiment analysis
nltk            — text preprocessing
wordcloud       — text visualization
jupyter         — interactive notebooks
```

## Project Structure

```
├── level1/          # Basic: Cleaning, EDA, Visualization
├── level2/          # Intermediate: Regression, Clustering
OAOAOA├── level3/          # Advanced: Classification, NLP
└── requirements.txt
```

## Setup

```bash
git clone https://github.com/YOURUSERNAME/codveda-data-analytics-internship
cd codveda-data-analytics-internship
pip install -r requirements.txt
jupyter notebook
```

## Internship

OAOAOA**Organization:** Codveda Technology  
OAOAOA**Domain:** Data Analytics / Data Science  
**Duration:** 1 Month  

OAOAOA#CodvedaJourney #CodvedaExperience #FutureWithCodveda
