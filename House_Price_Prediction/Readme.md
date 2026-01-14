# 🏠 House Price Prediction – Machine Learning Assignment

## 📌 Project Overview

This project focuses on building and evaluating multiple Machine Learning models to predict house prices based on various structural and locational features. The assignment follows a structured data science workflow, including data understanding, preprocessing, visualization, model building, hyperparameter tuning, and performance comparison.

A complete Jupyter Notebook and a video walkthrough explaining the approach and results are provided as part of the submission.

## 📂 Dataset Description

The dataset consists of three CSV files:

| File Name | Description |
|-----------|-------------|
| `train.csv` | Training dataset containing features and target variable (price) |
| `test.csv` | Test dataset with target column hidden |
| `sample_submission.csv` | Sample format for final predictions |

### 🔑 Feature Description

| Column Name | Description |
|-------------|-------------|
| `id` | Unique identifier |
| `area_type` | Type of area |
| `availability` | Availability status of the house |
| `location` | Geographical location |
| `size` | Configuration (BHK – Bedrooms, Hall, Kitchen) |
| `total_sqft` | Total area in square feet |
| `bath` | Number of bathrooms |
| `balcony` | Number of balconies |
| `price` | House price (Target Variable) |

## 🧪 Project Workflow

The notebook follows a clear and structured pipeline as per the assignment rubrics:

### 1️⃣ Data Understanding
- Identified data types of all columns
- Converted inconsistent columns (e.g., `total_sqft`, `size`) into usable numeric formats

### 2️⃣ Exploratory Data Analysis (EDA)
- Generated descriptive statistics (min, max, mean, median)
- Visualized distributions and relationships between features and target

### 3️⃣ Data Cleaning
- Missing values identified and handled (imputation or removal)
- Duplicate records checked and removed where applicable
- Outliers detected using statistical methods and domain reasoning

### 4️⃣ Data Visualization
At least three meaningful visualizations were created, such as:
- Price distribution
- Price vs total square feet
- Price variation across locations / BHK types

Each visualization is accompanied by insightful interpretations.

### 5️⃣ Feature Engineering
- Scaling of numerical features where required
- Encoding of categorical variables using appropriate techniques
- Justification provided for scaling and encoding choices

## 🤖 Model Building

A minimum of 7 Machine Learning models were trained and evaluated, including (but not limited to):
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost / Extra Trees / SVR

## ⚙️ Hyperparameter Tuning

Hyperparameter optimization was performed on at least 3 models using techniques such as:
- GridSearchCV
- RandomizedSearchCV

## 📊 Model Evaluation & Comparison

- Models were evaluated using appropriate regression metrics (e.g., RMSE, R²)
- Performance comparison was conducted on a validation set
- Best-performing model was selected based on results and interpretability

## 📈 Final Output

- Predictions generated on `test.csv`
- Submission file created in the format of `sample_submission.csv`

## 🎥 Video Walkthrough

A detailed video explanation of the notebook is available here:

🔗 **Video URL:** [Add your Google Drive link here]

## 🧑‍💻 Tools & Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 📝 Notes

- Peer Review is mandatory (5 reviews required post-submission)
- Code is written with readability, modularity, and reproducibility in mind
- Comments and markdown cells explain logic and decisions clearly

## ✅ Conclusion

This project demonstrates a complete end-to-end Machine Learning regression workflow, from raw data to validated predictions, following best practices in data preprocessing, model development, and evaluation.
