# Data Analysis and Classification with Python

## Project Overview
## Task 5 - Data Analysis and Data Science with Python  
The project covers **two different real-world problems** using **two different CSV datasets**:

1. **Student Pass/Fail Prediction**
2. **Sentiment Analysis using Natural Language Processing (NLP)**

Both tasks use **Logistic Regression** and follow a complete **data science workflow** including data exploration, preprocessing, model training, evaluation, and insights.

---

## Tools & Technologies Used
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- NLTK (for NLP)
- TF-IDF Vectorization

---

## Dataset Details

### 1. Student Performance Dataset
**File:** `student_performance_dataset.csv`

**Columns:**
- `StudyHours` – Number of hours studied per week
- `Attendance` – Percentage of classes attended
- `Pass` – Target variable (1 = Pass, 0 = Fail)

**Purpose:**
Predict whether a student will pass or fail based on study habits and attendance.

---

### 2. Sentiment Dataset
**File:** `Sentiment_Data.csv`

**Columns:**
- `Review` – Customer review text
- `Sentiment` – Sentiment label (`positive` / `negative`)

**Purpose:**
Classify customer reviews into positive or negative sentiments using NLP techniques.

---

## Task 1: Student Pass/Fail Prediction

### Steps Performed
1. Load and explore the dataset
2. Check for missing values
3. Visualize Study Hours vs Attendance
4. Select features and target variable
5. Split data into training and testing sets (80:20)
6. Train a Logistic Regression model
7. Evaluate using:
   - Accuracy Score
   - Confusion Matrix
8. Analyze key predictors of student performance

### Model Used
- Logistic Regression

### Evaluation Metrics
- Accuracy
- Confusion Matrix

### Key Insights
- Higher study hours significantly increase the probability of passing
- Attendance strongly influences student performance
- Logistic Regression performs well for binary classification

---

## Task 2: Sentiment Analysis using NLP

### Steps Performed
1. Load and inspect the dataset
2. Clean text data:
   - Convert to lowercase
   - Remove punctuation and special characters
3. Convert text into numerical form using TF-IDF
4. Split data into training and testing sets
5. Train Logistic Regression classifier
6. Evaluate model using:
   - Accuracy
   - Precision
   - Recall
   - F1-score

### Model Used
- Logistic Regression with TF-IDF Vectorization

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

### Key Insights
- Positive reviews commonly include words like *excellent, amazing, great*
- Negative reviews often include *bad, poor, worst*
- TF-IDF improves text classification performance

---
3. Run notebooks cell by cell to see outputs and explanations

---

## Learning Outcomes
- Understanding of classification problems
- Hands-on experience with Logistic Regression
- Practical NLP preprocessing and sentiment analysis
- Model evaluation using multiple metrics
- Real-world data analysis workflow

---

