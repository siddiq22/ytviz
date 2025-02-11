# 📊 YouTube Data Analysis: Insights from Data Analyst Channels

## 📌 Project Overview

YouTube is one of the largest content-sharing platforms, attracting millions of viewers daily. However, what makes certain videos more successful than others? Does engagement (likes, comments) influence viewership? Are certain upload days or video attributes linked to higher views?

This project analyzes 9 popular Data Analyst YouTube channels to uncover insights about video performance, engagement, and content strategies.

### ✅ Data Source: Google YouTube Data API v3
### ✅ Tools Used: Python, Pandas, Matplotlib, Seaborn, NLTK, WordCloud
### ✅ Dataset: 3,939 videos from Alex The Analyst, Corey Schafer, Ken Jee, Mo Chen, Luke Barousse, Data Professor, Tech With Tim, Data Science Jay, Nicholas Renotte, and StatQuest with Josh Starmer

## 🎯 Objectives
In this project, we aim to answer key questions, including:

📊 Which channels have the highest total view counts?

📅 Do upload days/months impact video performance?

🔗 How do views correlate with likes, tags, and comments?

⏳ What is the typical duration of videos?

🗣️ What are the most frequently used words in video titles and comments?

🔤 Does title length affect view count?

## 📂 Data Collection & Preprocessing

1️⃣ Gathered video data using the YouTube API for the selected channels.

2️⃣ Extracted metadata, including views, likes, comments, tags, duration, upload dates.

3️⃣ Converted timestamps, cleaned missing data, and processed text data for NLP analysis.

## 📊 Visualizations & Insights

### Total Views Per Channel
📌 Bar chart comparing total views across all channels

### Views vs. Likes, Tags, and Comments (Scatter Plots)
📌 Shows the correlation between engagement metrics and views

### Video Duration Distribution
📌 Histogram showing how long most videos are

### Most Used Words in Video Titles (Word Cloud)
📌 Highlights the most frequent words in video titles

## 📉 Limitations & Future Work
🔹 This dataset includes only 3,939 videos from 9 channels, which does not represent all Data Analyst YouTube content.

🔹 Only the first 10 comments per video were analyzed, so broader sentiment analysis could yield better insights.

🔹 Factors like video quality, thumbnails, and algorithm recommendations were not considered.

🔹 Future work could involve predicting video performance based on content attributes using Machine Learning.

## 📂 Files & Notebooks

📄 YouTube_Analysis.ipynb → Full Python notebook with data collection, EDA, and visualizations.

📄 images/ → Contains visualization images used in this report.

## 🔗 Resources & Data Source

YouTube Data API v3 → YouTube API Docs

Google Cloud Console → Manage API Keys

## 📢 Conclusion

This project provides valuable insights into YouTube engagement trends for Data Analyst channels.

By analyzing key metrics like views, likes, comments, and video length, we identified factors that contribute to video success.

### 📌 Want to explore the data? Check out the notebook and interactive visualizations!

### 🚀 Feel free to contribute, fork, or raise issues for improvements!
