# Google Play Store Apps — Exploratory Data Analysis

This project analyzes apps and user reviews from the **Google Play Store** using Python, Pandas, Seaborn, Matplotlib, and VADER for sentiment analysis.

The notebook explores both **app metadata** (category, installs, ratings, price, type) and **user reviews** (positive/negative/neutral sentiment), generating meaningful insights and visualizations.

## Project Highlights

- Top categories by number of apps  
- Free vs Paid apps distribution  
- Ratings distribution across apps  
- Categories with most installs  
- Top apps by installs  
- Reviews vs installs correlation  
- Sentiment analysis of user reviews using **VADER**  
- Average sentiment per category  
- Top apps by average sentiment  
- Wordcloud of negative reviews for specific categories  

## Files

- `googleplaystore.csv` — App metadata  
- `googleplaystore_user_reviews.csv` — User reviews  
- `EDA_GooglePlayStore.ipynb` — Main notebook with explanations, charts, and sentiment analysis  
- `apps_cleaned.csv` — Cleaned app data  
- `reviews_with_vader.csv` — Reviews with VADER sentiment (if available)  
- `apps_with_sentiment.csv` — Apps merged with review sentiment (if computed)  

## How to Run

1. Open the notebook `EDA_GooglePlayStore.ipynb` in **Google Colab**.
2. Upload the CSV files (or place them in `/mnt/data`).
3. Run each cell sequentially — text cells explain the charts, code cells generate the plots.
4. Optionally, export the notebook as PDF for reports or presentations.

## Insights

The notebook provides **10+ visual insights** including bar charts, scatter plots, histograms, and wordclouds. It helps understand app trends, popularity, and user sentiment.

## Tools & Libraries

- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- VADER Sentiment Analysis  
- WordCloud  

---

**Author:** Surya Kumar  
**Date:** 2025
