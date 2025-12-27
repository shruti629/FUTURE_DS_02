# 🎓 Student Feedback Sentiment Analysis  
### University of Exeter | StudentCrowd Reviews

## 📌 Project Overview
This project focuses on analyzing student feedback collected from **StudentCrowd** for the **University of Exeter (UK)**.  
The goal is to transform unstructured student reviews into meaningful insights using **Natural Language Processing (NLP)** and data visualization techniques.

The analysis helps understand:
- Overall student sentiment
- Relationship between textual feedback and numeric ratings
- Areas requiring improvement based on negative sentiment patterns

---

## 🎯 Objectives
- Clean and preprocess real-world student feedback data
- Perform **sentiment analysis** on review text
- Classify reviews into **Positive, Neutral, and Negative**
- Visualize sentiment patterns and rating distributions
- Provide **data-driven recommendations** for improvement

---

## 📂 Dataset Description
The dataset was sourced from OpenDataBay.

### Key Columns:
- `reviews` – Textual feedback provided by students
- `member_id` – Unique identifier for each reviewer
- `date` – Date the review was submitted
- `overall_rating_out_of_5` – Overall university rating (1–5)
- `campus_facilities` – Rating for campus and facilities
- `club_societies` – Rating for clubs and societies
- `careers_service` – Rating for career services
- `wifi_internet` – Rating for Wi-Fi and internet facilities

---

## 🧠 Methodology

### 1️⃣ Data Cleaning
- Standardized column names
- Removed missing review text
- Converted date column to datetime format

### 2️⃣ Sentiment Analysis (NLP)
- Used **TextBlob** to compute sentiment polarity
- Polarity score range:
  - `> 0` → Positive
  - `= 0` → Neutral
  - `< 0` → Negative

### 3️⃣ Visualization
- Sentiment distribution plots
- Boxplots to compare sentiment vs numeric ratings
- Trend analysis to understand student satisfaction patterns

---

## 📊 Tools & Technologies Used
- **Python**
- **Pandas & NumPy** – Data manipulation
- **TextBlob** – Sentiment analysis
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive analysis

---

## 🔍 Key Insights
- Majority of student reviews express **positive sentiment**
- Negative sentiment commonly relates to:
  - Wi-Fi connectivity issues
  - Limited career guidance
  - Inconsistent club engagement
- Strong alignment observed between sentiment labels and numeric ratings

---

## ✅ Recommendations
- Improve campus-wide Wi-Fi infrastructure
- Enhance career services through workshops and industry interactions
- Increase visibility and accessibility of clubs and societies
- Continuously monitor feedback using NLP dashboards



