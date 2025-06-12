# ✈️ US Twitter Airline Sentiment Analysis

This project analyzes public sentiment towards major US airlines based on tweets. Using Natural Language Processing (NLP), it explores customer satisfaction, complaints, and brand perception on Twitter.

## 🧰 Tools & Technologies
- Python (pandas, matplotlib, seaborn, scikit-learn)
- Natural Language Toolkit (NLTK)
- WordCloud, TextBlob, CountVectorizer
- Jupyter Notebook

## 📊 Dataset
- **Source**: [Kaggle – US Airline Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
- 14,640 tweets labeled as positive, negative, or neutral

## 📌 Objectives
- Clean and preprocess Twitter text data
- Visualize sentiment distribution
- Identify most frequently used positive/negative words
- Build a sentiment classifier using logistic regression

## 🔍 Key Insights
- Over **60% of tweets** were negative, mainly driven by flight delays and poor service
- **United Airlines** had the highest number of complaints
- Common complaint keywords included: *"delayed"*, *"cancelled"*, *"customer service"*

## 🧠 ML Model Summary
- Model: Logistic Regression
- Accuracy: ~79%
- Top predictors: *"delayed"*, *"thank"*, *"worst"*

## 📷 Visual Highlights
![Sentiment Distribution_Twitter Analysis](https://github.com/user-attachments/assets/81aa46bc-838b-420f-8dc1-bb78690c53fa)
![Confusion Matrix_Twitter Sentiment Analysis](https://github.com/user-attachments/assets/d477dc03-502c-467b-8063-8c460ff6981c)
![WordCloud_Twitter Sentiment Analysis](https://github.com/user-attachments/assets/ab9f5110-e6ae-421b-988a-0055479d77f0)

## 📁 Folder Structure
/US_Twitter_Sentiment_Analysis
├── notebook/
├── visuals/
└── README.md
