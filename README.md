# 📊 YouTube Data Analysis: Insights from Data Analyst Channels

## 📌 Project Overview

YouTube is one of the largest content-sharing platforms, attracting millions of viewers daily. However, what makes certain videos more successful than others? Does engagement (likes, comments) influence viewership? Are certain upload days or video attributes linked to higher views?

This project analyzes 9 popular Data Analyst YouTube channels to uncover insights about video performance, engagement, and content strategies.

✅ Data Source: Google YouTube Data API v3
✅ Tools Used: Python, Pandas, Matplotlib, Seaborn, NLTK, WordCloud
✅ Dataset: 3,939 videos from Alex The Analyst, Corey Schafer, Ken Jee, Mo Chen, Luke Barousse, Data Professor, Tech With Tim, Data Science Jay, Nicholas Renotte, and StatQuest with Josh Starmer

🎯 Objectives
In this project, we aim to answer key questions, including:

📊 Which channels have the highest total view counts?
📅 Do upload days/months impact video performance?
🔗 How do views correlate with likes, tags, and comments?
⏳ What is the typical duration of videos?
🗣️ What are the most frequently used words in video titles and comments?
🔤 Does title length affect view count?
📂 Data Collection & Preprocessing
1️⃣ Gathered video data using the YouTube API for the selected channels.
2️⃣ Extracted metadata, including views, likes, comments, tags, duration, upload dates.
3️⃣ Converted timestamps, cleaned missing data, and processed text data for NLP analysis.

🔎 Key Findings & Insights
📊 1. Total Views Per Channel
Tech With Tim leads in total views with 163M+ views, while Jay Feng has the lowest at 3.5M+ views.
Channels with consistent uploads and strong engagement tend to have higher viewership.
📅 2. Video Upload Trends
Most videos are uploaded on weekdays, with Tuesdays being the most common.
The first and last 3 months of the year see the highest upload activity.
🔗 3. Engagement Analysis (Views vs. Likes & Comments)
Likes have a stronger correlation with views than comments.
More engaging videos receive higher likes, reinforcing the importance of audience interaction.
⏳ 4. Video Duration Trends
Most videos are between 5-60 minutes long.
The longest video is ~2 hours 13 minutes, but shorter videos seem to perform better.
🗣️ 5. Most Common Words in Titles & Comments
"Python" is the most frequently used word in both video titles and comments.
Other popular words include "data science," "machine learning," and "analytics."
📊 Visualizations & Insights
Total Views Per Channel
📌 Bar chart comparing total views across all channels

Views vs. Likes, Tags, and Comments (Scatter Plots)
📌 Shows the correlation between engagement metrics and views

Video Duration Distribution
📌 Histogram showing how long most videos are

Most Used Words in Video Titles (Word Cloud)
📌 Highlights the most frequent words in video titles

📉 Limitations & Future Work
🔹 This dataset includes only 3,939 videos from 9 channels, which does not represent all Data Analyst YouTube content.
🔹 Only the first 10 comments per video were analyzed, so broader sentiment analysis could yield better insights.
🔹 Factors like video quality, thumbnails, and algorithm recommendations were not considered.
🔹 Future work could involve predicting video performance based on content attributes using Machine Learning.

📂 Files & Notebooks
📄 YouTube_Analysis.ipynb → Full Python notebook with data collection, EDA, and visualizations.
📄 data/youtube_videos.csv → Processed dataset.
📄 images/ → Contains visualization images used in this report.

🔗 Resources & Data Source
YouTube Data API v3 → YouTube API Docs
Google Cloud Console → Manage API Keys
📢 Conclusion
This project provides valuable insights into YouTube engagement trends for Data Analyst channels.
By analyzing key metrics like views, likes, comments, and video length, we identified factors that contribute to video success.

📌 Want to explore the data? Check out the notebook and interactive visualizations!

🚀 Feel free to contribute, fork, or raise issues for improvements!
