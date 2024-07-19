# PUBG Final Placement Prediction

This project aims to predict the final placement of players in PUBG matches using machine learning techniques. The dataset used contains various player statistics and match details. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering](#feature-engineering)
- [Model Selection](#model-selection)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Innovation](#innovation)
- [Programming Skills](#programming-skills)
- [Database Knowledge](#database-knowledge)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [How to Run](#how-to-run)

## Introduction

This project uses a machine learning approach to predict the final placement of players in PUBG matches. By analyzing player statistics and match data, we aim to develop a robust model that can accurately predict match outcomes.

## Dataset Overview

The dataset contains information about various aspects of PUBG matches, including:
- Player statistics (kills, assists, damage dealt, etc.)
- Match duration and placement

The data is preprocessed to handle missing values and normalize features for better model performance.

## Exploratory Data Analysis (EDA)

Key observations from the data include:
- Distribution of kills
- Correlation between features

Visualizations help understand data distribution and relationships, aiding in feature selection and engineering.

## Feature Engineering

New features are created to improve model performance:
- **Total Kills:** Sum of kills and assists
- **Average Damage:** Damage dealt per match duration

Feature scaling is applied to normalize the data.

## Model Selection

The RandomForestClassifier is selected for its robustness and performance. The model is trained and evaluated on the dataset using various metrics:
- Accuracy: 72%
- Precision, Recall, F1-score

## Model Training and Evaluation

The training process includes data splitting and cross-validation. Evaluation metrics used are:
- Accuracy
- Precision
- Recall
- F1 Score

The results show a good balance between precision and recall.

## Innovation

Unique aspects of the project include:
- Feature engineering
- Model tuning

Problem-solving approaches involve hyperparameter tuning for optimal performance.

## Programming Skills

Key parts of the code focus on model implementation and data processing using tools like Python, Pandas, and Scikit-learn.

## Database Knowledge

Data management and storage are handled efficiently with pandas and SQL. Example SQL query:
```sql
SELECT * FROM pubg_matches WHERE match_id = 1;
```

## Conclusion

The model achieved an accuracy of 72%. Feature engineering and hyperparameter tuning were crucial in achieving this performance.

## Future Work

Future improvements could include:
- Exploring advanced models like XGBoost and deep learning approaches
- Enhancing feature engineering
- Improving data preprocessing techniques for better model performance

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Chetupatil24/pubg.git
   cd pubg
   ```

2. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the preprocessing script:**
   ```bash
   python preprocess.py
   ```

4. **Run the model training script:**
   ```bash
   python train_model.py
   ```

5. **Evaluate the model:**
   ```bash
   python evaluate_model.py
   ```

## Contact

For any questions or further information, please contact:
- **Name:** Chethan N Patil
- **Email:** chetupatil605@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/chethan-n-patil-303a10252/
