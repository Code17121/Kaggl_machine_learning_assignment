# 🏨 Hotel Booking Cancellation Prediction – Machine Learning Assignment

## 📌 Project Overview

This project aims to predict whether a customer will cancel their hotel booking using Machine Learning techniques. The assignment is conducted on the Kaggle platform, where model performance is evaluated on the leaderboard based on prediction accuracy.

The notebook follows a structured end-to-end data science workflow including data understanding, preprocessing, exploratory data analysis, feature engineering, model building, hyperparameter tuning, and performance comparison.

A complete Kaggle Notebook and a video walkthrough explaining the approach and insights are provided as part of the submission.

## 🏁 Competition Details

- **Platform:** Kaggle
- **Start Date:** Nov 11, 2025
- **End Date:** Nov 20, 2025
- **Evaluation Metric:** Accuracy
- **Competition Link:** https://www.kaggle.com/t/acbc86871ce144a197ea032dda27b689

> Marks are awarded only if the submission appears on the Kaggle leaderboard and crosses the cutoff score.

## 📂 Dataset Description

The dataset consists of three CSV files:

| File Name | Description |
|-----------|-------------|
| `train.csv` | Training dataset containing features and target variable (booking_status) |
| `test.csv` | Test dataset with target column hidden |
| `sample_submission.csv` | Sample submission file in the correct format |

### 🔑 Feature Description

| Column Name | Description |
|-------------|-------------|
| `id` | Unique identifier |
| `adults` | Number of adults |
| `children` | Number of children |
| `weekends` | Number of weekend days |
| `weekdays` | Number of weekday days |
| `meal_type` | Meal type selected |
| `room_type` | Room type selected |
| `arrival` | Arrival date |
| `lead_time` | Days between booking and arrival |
| `segment` | Booking segment |
| `repeat` | Whether customer is a repeat guest |
| `price` | Average price per room |
| `requests` | Number of special requests |
| `booking_status` | Target variable (1 = Cancelled, 0 = Not Cancelled) |

## 🧪 Project Workflow

The notebook strictly follows the peer-review rubrics provided for evaluation.

### 1️⃣ Data Understanding
- Identified and explicitly stated data types of all columns
- Converted date and categorical columns into appropriate formats

### 2️⃣ Exploratory Data Analysis (EDA)
- Generated descriptive statistics including minimum, maximum, mean, and median
- Studied feature distributions and relationships with booking cancellation

### 3️⃣ Data Cleaning
- Identified and handled missing values through imputation or removal
- Checked for duplicate records and removed them where applicable
- Detected outliers using statistical methods and provided justification for handling

### 4️⃣ Data Visualization
At least three meaningful visualizations were created, including:
- Distribution of booking cancellations
- Price vs booking cancellation status
- Lead time vs cancellation behavior

Each visualization is supported with clear insights.

### 5️⃣ Feature Engineering
- Scaled numerical features where required
- Encoded categorical features using suitable techniques
- Provided reasoning for scaling and encoding decisions

## 🤖 Model Building

The following **9 Machine Learning models** were trained and evaluated using the same train-validation split:

1. Logistic Regression
2. SGDClassifier
3. Perceptron
4. K-Nearest Neighbors (KNN) Classifier
5. Ridge Classifier
6. Decision Tree Classifier
7. Random Forest Classifier
8. XGBoost Classifier
9. LightGBM (LGBM) Classifier

This satisfies the requirement of training at least 7 different models.

## ⚙️ Hyperparameter Tuning

Hyperparameter tuning was performed on three models using:
- GridSearchCV
- RandomizedSearchCV

**Tuned models include:**
- Random Forest Classifier
- XGBoost Classifier
- LightGBM Classifier

## 📊 Model Evaluation & Comparison

- Models were evaluated using validation accuracy
- Performance of all models was compared visually and numerically
- Tree-based ensemble models (Random Forest, XGBoost, LightGBM) achieved the highest accuracy
- The final model was selected based on validation performance and generalization ability

## 📈 Submission Format

Predictions were generated for the test dataset in the following format:

```csv
id,booking_status
0,1
1,0
2,1
...
```

## 🎥 Video Walkthrough

A video walkthrough (8–12 minutes) explaining the notebook, models, and insights is available below:

🔗 **Video URL:** https://drive.google.com/file/d/1YTMM0tOL5IjlNgKwtMckW8-kZWrZ175q/view?usp=sharing

## 🧑‍💻 Tools & Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost, LightGBM
- Kaggle Notebooks

## 📝 Notes

- Kaggle submission above cutoff is mandatory for grading
- Completion of 5 peer reviews is required post-submission
- Code emphasizes readability, modularity, and reproducibility
- Markdown explanations clearly justify modeling decisions

## ✅ Conclusion

This project demonstrates a complete end-to-end Machine Learning classification workflow on a real-world dataset, covering data preprocessing, visualization, feature engineering, model training, hyperparameter tuning, and leaderboard-based evaluation.
