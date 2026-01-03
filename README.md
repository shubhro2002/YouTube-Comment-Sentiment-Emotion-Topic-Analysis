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

- 

# 📈 Future Work

- Deploy interactive dashboard with Streamlit / Power BI / Looker Studio
- Fine-tune sarcasm/emotion models on domain-specific data
