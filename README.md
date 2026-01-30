# Web-Blog-Sentiment-Analysis-System

## 📌 Project Overview
This project is an NLP-based system that analyzes blogs related to a user-provided keyword.  
It searches the web using APIs, collects accessible blog URLs, analyzes blog comments, and extracts meaningful insights through sentiment analysis and visualizations.

## 🔍 How It Works
1. The user provides a **keyword** (e.g., *Data Science*).
2. The system searches the browser using an API for blogs related to that keyword.
3. Blogs that **restrict crawling using `robots.txt`** are automatically skipped.
4. URLs of accessible blogs are collected.
5. The system:
   - Extracts comments from blogs
   - Generates an automatic comment
   - Performs **sentiment analysis** on existing comments
6. Results are visualized using:
   - **Pie charts** for sentiment distribution
   - **Word clouds** for most common keywords

## 🧠 Features
- Keyword-based blog search using API
- Respect for `robots.txt` rules
- Automatic blog URL extraction
- Auto-generated comments
- Comment-based sentiment analysis (Positive, Neutral, Negative)
- Pie chart visualization of sentiment
- Word cloud of most frequent words

## 🛠️ Technologies Used
- Python  
- Natural Language Processing (NLP)
- Sentiment Analysis
- Web APIs
- Data Visualization Libraries

## 📊 Output
- Sentiment distribution (Positive / Neutral / Negative)
- Visual pie charts
- Word cloud showing most common terms
- List of accessible blog URLs

## 🎯 Use Cases
- Blog content analysis
- Market and trend research
- Public opinion analysis
- Academic and NLP learning projects

## 🚀 Future Improvements
- Support for multiple keywords
- Advanced sentiment models
- Dashboard-based visualization
- Language detection and multilingual support


