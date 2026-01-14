# 🎬 Movie Review Sentiment Prediction – Machine Learning Assignment

## 📌 Project Overview

This project focuses on predicting the sentiment of movie reviews using Machine Learning techniques. The task is a multi-class classification problem, where each review is classified as negative (0), neutral (1), or positive (2).

The assignment is conducted on the Kaggle platform, and model performance is evaluated on the leaderboard based on prediction accuracy. Only submissions that appear on the leaderboard and cross the cutoff score are considered for grading.

A complete Kaggle Notebook and a video walkthrough explaining the methodology and insights are provided as part of the submission.

## 🏁 Competition Details

- **Platform:** Kaggle
- **Start Date:** Dec 2, 2025
- **End Date:** Dec 11, 2025
- **Evaluation Metric:** Accuracy
- **Competition Link:** https://www.kaggle.com/t/bdfe59603f7a49819e1888c5b35cadb5

## 📂 Dataset Description

The dataset is provided by a movie review platform aiming to analyze user sentiments.

### Files Provided

| File Name | Description |
|-----------|-------------|
| `train.csv` | Training dataset containing features and target variable (sentiment) |
| `test.csv` | Test dataset with target column hidden |
| `sample_submission.csv` | Sample submission file in the correct format |

### 🔑 Feature Description

| Column Name | Description |
|-------------|-------------|
| `id` | Unique identifier |
| `phrase` | Movie review text |
| `feature_1` | Engineered feature derived from the review |
| `feature_2` | Engineered feature derived from the review |
| `feature_3` | Engineered feature derived from the review |
| `sentiment` | Target variable (0 = Negative, 1 = Neutral, 2 = Positive) |

## 🧪 Project Workflow

The notebook strictly follows the peer-review rubrics provided for evaluation.

### 1️⃣ Data Understanding
- Identified and explicitly stated data types of all columns
- Examined text and numerical feature distributions

### 2️⃣ Exploratory Data Analysis (EDA)
- Generated descriptive statistics for numerical features (min, max, mean, median)
- Analyzed sentiment class distribution

### 3️⃣ Data Cleaning
- Identified and handled missing values
- Checked for duplicate records and removed them where applicable
- Detected outliers in numerical features and justified retention or removal

### 4️⃣ Data Visualization
At least three meaningful visualizations were created, including:
- Sentiment class distribution
- Feature distributions
- Relationship between engineered features and sentiment

Each visualization includes clear insights.

### 5️⃣ Feature Engineering
- Text preprocessing applied to review phrases
- Numerical features scaled where required
- Categorical variables encoded using appropriate techniques
- Clear justification provided for scaling and encoding choices

## 🤖 Model Building

The following **8 Machine Learning models** were trained and evaluated:

1. LinearSVC
2. Logistic Regression
3. Complement Naive Bayes
4. Multinomial Naive Bayes
5. SGDClassifier
6. XGBoost Classifier
7. Random Forest Classifier
8. Gaussian Naive Bayes

This satisfies the requirement of training at least 7 different models.

### Model Performance Comparison

| Model | Accuracy |
|-------|----------|
| LinearSVC | 0.6300 |
| Logistic Regression | 0.6293 |
| Complement Naive Bayes | 0.6250 |
| Multinomial Naive Bayes | 0.6200 |
| SGDClassifier | 0.6121 |
| XGBoost Classifier | 0.5500 |
| Random Forest Classifier | 0.5350 |
| Gaussian Naive Bayes | 0.4871 |

## ⚙️ Hyperparameter Tuning

Hyperparameter tuning was performed on 3 models using:
- GridSearchCV
- RandomizedSearchCV

**Tuned models include:**
- LinearSVC
- Logistic Regression
- Multinomial Naive Bayes

## 📊 Model Evaluation & Comparison

- Models evaluated using validation accuracy
- Performance of all models compared on a validation set
- LinearSVC achieved the highest accuracy (0.6300)
- Best-performing model selected based on accuracy and generalization ability

## 📈 Submission Format

Predictions were generated for the test dataset in the following format:

```csv
id,sentiment
0,1
1,2
2,0
...
```

## 🎥 Video Walkthrough

A video walkthrough (8–12 minutes) explaining the notebook, models, and insights is available below:

🔗 **Video URL:** https://drive.google.com/file/d/1WC5ZSeRilobxX64-rTGQ3Qh1m6fqo7Kk/view?usp=sharing

> Ensure access is set to "Anyone with the link – Viewer"

## 📁 Repository Structure

```
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
├── notebook/
│   └── Movie_Review_Sentiment_Prediction.ipynb
├── submission/
│   └── submission.csv
└── README.md
```

## 🧑‍💻 Tools & Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Natural Language Processing (NLP) techniques
- Kaggle Notebooks

## 📝 Notes

- Kaggle submission above cutoff score is mandatory for marks
- Completion of 5 peer reviews is required post-submission
- Code emphasizes readability, modularity, and reproducibility
- Markdown explanations clearly justify modeling decisions

## ✅ Conclusion

This project demonstrates a complete end-to-end Machine Learning and NLP classification workflow, covering text preprocessing, feature engineering, model training, hyperparameter tuning, and leaderboard-based evaluation on a real-world sentiment analysis task.
