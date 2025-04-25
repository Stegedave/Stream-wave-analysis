# StreamWave Churn Analysis

A one-day data science case study exploring customer churn for **StreamWave**, a fictional video streaming service. The goal is to identify churn patterns, build a predictive model, and recommend strategies to improve user retention.

---

## 📊 Project Overview

StreamWave has been experiencing increased user churn. This project explores the factors driving cancellations and presents actionable recommendations to reduce churn.

### Objectives:
- Perform exploratory data analysis (EDA) on user behavior data
- Build a churn classification model
- Communicate key insights and propose retention strategies

---

## 📁 Dataset

File: `data/user_behavior.csv`  
Each row represents a unique user with the following features:

| Feature | Description |
|--------|-------------|
| `user_id` | Unique user identifier |
| `account_age_days` | Number of days since account creation |
| `total_hours_watched` | Total hours of content watched |
| `num_genres_watched` | Number of unique genres watched |
| `avg_watch_time_per_day` | Average hours watched per day |
| `num_devices` | Number of devices used |
| `support_tickets_opened` | Number of support tickets submitted |
| `churned` | Binary label (0 = active, 1 = churned) |

---

## 🔍 Key Steps

### 1. Exploratory Data Analysis (EDA)
- Summary statistics & missing value checks
- Visualizations of churn vs non-churn users
- Correlation analysis

### 2. Model Building
- Train/test split
- Logistic Regression and/or Random Forest
- Evaluation: Accuracy, Precision, Recall
- Feature importance analysis

### 3. Business Recommendations
- Targeted re-engagement for low-engagement users
- Proactive support for users with open tickets
- Personalized content suggestions based on genre preferences

---

## 🛠️ Tech Stack

- Python (3.8+)
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📄 Deliverables

- 📓 `notebooks/churn_analysis.ipynb` – Full analysis & modeling
- 📊 `reports/churn_findings.pdf` – (Optional) Summary presentation for stakeholders

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Stegedave/Stream-wave-analysis
   cd Stream-wave-analysis
