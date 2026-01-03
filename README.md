# 🎭 YouTube Comment Sentiment, Emotion & Topic Analysis

## Project Overview

This project analyzes YouTube comments to extract insights about audience sentiment, emotions, sarcasm, and discussion topics. The pipeline combines text preprocessing, sentiment analysis, sarcasm detection, emotion classification, and topic modeling to deliver a comprehensive understanding of community engagement.

## 🚀 Features

- ✅ Automated data collection from YouTube API
- ✅ Data cleaning & preprocessing pipeline (text, authors, replies, timestamps)
- ✅ Sentiment analysis (discrete + thread-aware)
- ✅ Sarcasm detection with wordclouds for sarcastic comments
- ✅ Emotion classification using Google’s GoEmotions model
- ✅ Topic modeling with BERTopic
- ✅ Keyword extraction with KeyBERT per sentiment class
- ✅ Rich visualizations (wordclouds, bar charts, emotion/sentiment distributions)

## 🛠️ Tech Stack

- Python (pandas, numpy, matplotlib, seaborn, wordcloud)

- NLP: HuggingFace Transformers (GoEmotions, sentiment models), BERTopic, KeyBERT

- Visualization: Matplotlib, WordCloud, Plotly

- Data: YouTube API

## 📊 Key Results

### Sentiment Distribution across 45,000+ comments

- % Positive, Negative, Neutral

- Thread-aware sentiment shifts

### Sarcasm Detection

- % of sarcastic comments

- Wordcloud of sarcasm-heavy terms

### Emotion Analysis (GoEmotions, 27 emotions)

- Top 5 most frequent emotions

- Wordcloud of some of the emotions

### Topic Modeling (BERTopic)

- Top topics discussed by viewers

- Representative keywords per topic

### Keyword Extraction

- Key phrases per sentiment/emotion
       - Thread-aware sentiment shifts
- Sarcasm Detection

# 📷 Visuals

## Topic Score
<img width="1113" height="482" alt="image 1" src="https://github.com/user-attachments/assets/61cc0d6c-d9cb-494a-9936-6cee152c6030" />

## Top 20 Most Discussed Threads
<img width="1141" height="747" alt="image 2" src="https://github.com/user-attachments/assets/9b03dbc6-0873-4f0f-8aa9-29d131c1342e" />

## Sentiment by Thread
<img width="1241" height="737" alt="image 3" src="https://github.com/user-attachments/assets/c87be315-c2a4-4ca8-a9ee-f5d2a8928123" />

## Number of Comments over Time
<img width="1221" height="652" alt="image 4" src="https://github.com/user-attachments/assets/3bf6ef8d-dcad-4be1-b758-036cea30a830" />

## Comments by Day
<img width="1062" height="662" alt="image 5" src="https://github.com/user-attachments/assets/a631dc2f-b335-48b8-a5ae-4138969633d6" />

## 
<img width="611" height="643" alt="image 6" src="https://github.com/user-attachments/assets/47ffeda9-341c-4e3d-83b0-f3a711ee5557" />


# 📈 Future Work

- Deploy interactive dashboard with Streamlit / Power BI / Looker Studio
- Fine-tune sarcasm/emotion models on domain-specific data
