# 🎥 YouTube Trending Videos — Exploratory Data Analysis

## 📊 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on the **YouTube Trending Videos** dataset from Kaggle.  
The main goal is to uncover what makes a video trend on YouTube — exploring metrics such as views, likes, comments, and categories across different countries.  
It helps identify patterns in publishing time, duration, engagement, and audience preferences.

---

## 🧱 Project Structure

youtube_eda_project/
├─ data/ # put CSV/JSON from Kaggle here (ignored by Git)
├─ youtube_eda.ipynb # main notebook
├─ requirements.txt # dependencies
└─ .gitignore # ignore rules

---

## ⚙️ How to Run (VS Code)
1. Open this folder in **VS Code**.  
2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   .\.venv\Scripts\activate

3. Install dependencies: pip install -r requirements.txt
4. Download dataset files from Kaggle: USvideos.csv and US_category_id.json, and place them inside the data/ folder.
5. Open youtube_eda.ipynb, set: COUNTRY = "US".

## 🛠️ Tools & Libraries
Python 3.11
pandas, numpy — data analysis and preprocessing
matplotlib, seaborn — data visualization

## 📈 Analysis Workflow
Load and inspect dataset.
Data cleaning & preprocessing: Remove duplicates, Handle missing values, Parse dates and durations.
Feature engineering: Calculate engagement metrics: like_ratio, comment_rate, tags_count.
Visualization & Insights: Views vs Likes correlation, Trending categories, Publish hour and weekday distribution, Country comparison, Like ratio by category.

## 🧠 Key Insights
🎬 Music and Entertainment are the top global trending categories.
⏰ Most trending videos are published between 15:00–20:00 local time.
💬 Shorter videos (<10 minutes) show higher engagement (likes/comments ratio).
🌍 USA, Mexico, and Japan datasets show similar engagement patterns.
🔥 Comedy and People & Blogs lead in like-to-view ratio.

## 🔗 Dataset Source: [Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)

## 💼 Business Relevance
These insights can help content creators and marketing teams understand which factors drive engagement on YouTube — such as timing, category, and video length — and optimize their publishing strategy to reach a wider audience.

🔙 [Back to Portfolio](https://github.com/BlladeRunner)
