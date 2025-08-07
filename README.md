# Sentiment_Analysis_Tweets
# 🧠 Sentiment Analysis on Tweets using Transformer & VADER Models

This project performs sentiment analysis on Tamil tweets using both Transformer-based (`HuggingFace Transformers`) and traditional lexicon-based (`VADER`) approaches. It provides detailed comparisons through visualizations and analysis.

## 📊 Features

- Load and explore Tamil tweet dataset
- Perform basic exploratory data analysis (EDA)
- Apply **Transformer-based Sentiment Analysis**
- Apply **VADER Sentiment Analysis**
- Compare and visualize:
  - Sentiment distributions
  - Agreement between both models
- Tabular presentation of sentiment results

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Plotly, Matplotlib, Seaborn
- HuggingFace Transformers
- NLTK (VADER SentimentIntensityAnalyzer)
- SciPy

---

## 📂 Dataset

The dataset is a CSV file named `updated_tamil_tweet_data.csv` containing Tamil-language tweets.

| Column | Description       |
|--------|-------------------|
| text   | The tweet content |

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/yourusername/tamil-tweet-sentiment-analysis.git
cd tamil-tweet-sentiment-analysis

🧪 Sentiment Analysis
✅ Transformer-based (HuggingFace)

Uses a pre-trained model pipeline from HuggingFace to analyze the sentiment (POSITIVE/NEGATIVE) of tweets.

from transformers import pipeline
sentiment_analysis = pipeline('sentiment-analysis')

✅ VADER (Lexicon-based)

Uses NLTK's VADER lexicon to perform sentiment classification into POSITIVE, NEGATIVE, and NEUTRAL.

from nltk.sentiment import SentimentIntensityAnalyzer

📈 Visualizations

    Distribution of Transformer vs VADER sentiment classes

    Pie charts for categorical sentiment proportions

    Bar plots of matching/differing labels between models

    Interactive tables comparing sentiment outputs

🔍 Comparison Strategy

The project compares both methods in terms of:

    Overall sentiment class distribution

    Agreement between models (same/different)

    Comparison with and without neutral records

Color-coded tables and charts provide a clear view of differences in sentiment assignments.
