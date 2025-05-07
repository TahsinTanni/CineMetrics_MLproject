# 🎥 CineMetrics_MLproject

A machine learning project designed to empower film producers and stakeholders with predictive insights into audience response. By analyzing various movie attributes, this project aims to classify films into rating categories such as *Excellent*, *Good*, *Average*, or *Poor*—enabling smarter investment and production decisions in the early stages.

---

## Project Objective

This project explores the relationship between a movie’s features—such as budget, cast, genre, and marketing—and its resulting audience reception, categorized into rating levels. By applying classification algorithms and neural networks, we aim to:

- Predict the **Rating_Category** of a movie before release
- Provide a data-driven framework for production planning
- Improve decision-making for marketing and investment strategies

---

## Dataset Description

The dataset consists of **1,200** movies, each with **12** features:

### Target Variable:
- `Rating_Category`: {**Excellent**, **Good**, **Average**, **Poor**}

### Feature Types:

#### Quantitative:
- `Director_Popularity`
- `Budget_MillionUSD`
- `Runtime_Minutes`
- `Release_Year`
- `Num_Main_Actors`
- `Avg_Actor_Popularity`
- `Num_Awards_Won`
- `Marketing_Spend_MillionUSD`

#### Categorical:
- `Genre`
- `Has_Famous_Producer`
- `Is_Sequel`
- `Rating_Category` (target)

---

## Machine Learning Techniques Used

- Logistic Regression
- Decision Trees
- Random Forest
- Neural Networks (Multi-Layer Perceptron)
- Cross-validation and Hyperparameter Tuning
- KNN

---

## 📚 Libraries Used

- `pandas` – data manipulation
- `numpy` – numerical operations
- `scikit-learn` – ML models and preprocessing
- `matplotlib` – visualization
- `seaborn` – enhanced visualization

---

## 📈 Workflow Overview

1. **Data Preprocessing**
   - Encoding categorical variables
   - Feature scaling
   - Handling missing values (if any)

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmaps
   - Distribution plots
   - Category imbalance checks

3. **Model Training**
   - Fit classification models on training data
   - Evaluate using accuracy, precision, recall, F1-score

4. **Neural Network Modeling**
   - Build and train an MLP classifier
   - Use validation metrics to evaluate performance

5. **Insights & Recommendation**
   - Feature importance analysis
   - Production and marketing strategies derived from model outputs

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/SmartMovieRatings.git
cd SmartMovieRatings
