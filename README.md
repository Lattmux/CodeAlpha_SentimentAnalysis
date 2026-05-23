# Twitter US Airline Sentiment Analysis

## Overview
This project performs Sentiment Analysis on the Twitter US Airline Sentiment dataset as part of the CodeAlpha Data Analytics Internship.

## Dataset
- **Source:** Kaggle - Crowdflower Twitter Airline Sentiment
- **Records:** 14,640 tweets
- **Features:** 15 columns including tweet text, airline sentiment, airline name and negative reason

## Analysis Steps
1. Loaded and explored the dataset structure
2. Checked for missing values and cleaned the data
3. Analysed sentiment distribution across all tweets
4. Examined sentiment by each airline
5. Identified top reasons for negative tweets
6. Applied TextBlob NLP to classify tweet sentiment
7. Compared TextBlob predictions with human labels
8. Visualized all findings with charts

## Key Findings
- Over 62% of airline tweets are negative
- Customer Service is the biggest complaint with 2,910 tweets
- United Airlines receives the most tweets overall
- Virgin America has the smallest tweet volume
- TextBlob and human labels sometimes disagree showing the complexity of sentiment in tweets

## Tools Used
- Python
- Pandas
- TextBlob
- Matplotlib
- Seaborn

## Files
- `Twitter_Airline_Sentiment_Analysis.ipynb` - Main Jupyter notebook
- `sentiment1_overall_distribution.png` - Overall sentiment distribution
- `sentiment2_by_airline.png` - Sentiment by airline chart
- `sentiment3_negative_reasons.png` - Top negative reasons chart
- `sentiment4_sentiment_percentage.png` - Sentiment percentage by airline
- `sentiment5_polarity_distribution.png` - Polarity score distribution

## Author
Lattmux - CodeAlpha Data Analytics Intern