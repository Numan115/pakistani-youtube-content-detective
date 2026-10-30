# 🇵🇰 Pakistani YouTube Content Detective (Jazz Pakistan Case Study)

An end-to-end data science and digital marketing analytics project analyzing **1,973+ videos** from the official **Jazz Pakistan** YouTube channel to uncover audience engagement patterns, content length dynamics, and publishing trends.

---

## 🚀 Project Overview
In the fast-evolving digital media landscape of Pakistan, telecom operators and brands heavily invest in video content. This project extracts, cleans, and analyzes historical YouTube data using Python to answer key marketing questions:
* What content formats and durations drive the highest audience engagement?
* How has publishing frequency evolved over the years (2015–2026)?
* What are the core correlations between views, likes, and comments on Pakistani branded content?

---

## 📊 Dataset & Features
The dataset was harvested directly using the **YouTube Data API v3**, containing the following metrics:
* **Video Metadata:** Video ID, Title, Publish Timestamp, Duration (converted to seconds).
* **Performance Metrics:** View Count, Like Count, Comment Count.
* **Engineered Features:** Engagement Rate (`(Likes + Comments) / Views`), Publication Year, Title Keyword Frequency.

---

## 🛠️ Tech Stack & Libraries
* **Python** (Core data processing)
* **Pandas & NumPy** (Data wrangling & manipulation)
* **Matplotlib & Seaborn** (Data visualization)
* **YouTube Data API v3** (Data extraction)

---
*Created as part of an AI & Data Science portfolio project.*
