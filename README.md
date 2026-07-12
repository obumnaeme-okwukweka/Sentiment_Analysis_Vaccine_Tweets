# CodeAlpha Sentiment Analysis — COVID-19 Vaccine Tweets

**Data Analytics Internship Project — CodeAlpha**

## 📌 Project Overview
This project analyzes public sentiment toward COVID-19 vaccines using a dataset of 193,343 tweets. Text data was cleaned and classified as Positive, Negative, or Neutral using VADER (a lexicon-based sentiment analysis tool), then visualized to identify overall sentiment patterns and trends over time.

## 📊 Dataset
- **Source:** [COVID-19 All Vaccines Tweets](https://www.kaggle.com/datasets/gpreda/all-covid19-vaccines-tweets) (Kaggle, by Gabriel Preda)
- **Size:** 193,343 tweets, 16 columns
- **Key fields used:** tweet text, date

## 🔍 Key Findings
1. **Sentiment distribution:** 33% positive, 51% neutral, 16% negative — public sentiment toward COVID-19 vaccines was predominantly neutral, with positive sentiment more than double negative sentiment.
2. **Positive tweets** commonly referenced vaccine availability and appointment updates. **Negative tweets** more often referenced side effects, distrust of specific manufacturers, and access/slot issues.
3. **Sentiment trend over time:** all three sentiment categories peaked around May–June 2021, likely reflecting the period of highest public discussion during vaccine rollout, then declined toward October as the topic became less prominent on Twitter.
4. **Limitations:** VADER is a lexicon-based tool, so it can miss sarcasm, context, and mixed sentiment. It's also tuned for general English text rather than medical terminology specifically.

## 🛠 Tools Used
- Python (Google Colab)
- pandas — data loading & cleaning
- VADER (vaderSentiment) — sentiment classification
- matplotlib & seaborn — data visualization

## 📁 Files
- `CodeAlpha_Sentiment_Analysis.ipynb` — full notebook with code, charts, and written analysis

## 📈 Visualizations Included
- Sentiment distribution (bar chart)
- Sentiment trend over time (line chart, Dec 2020–Oct 2021)

## 👤 Author
Obumnaeme-Okwukweka
[GitHub](https://github.com/obumnaeme-okwukweka) | Data Analyst Intern, CodeAlpha
