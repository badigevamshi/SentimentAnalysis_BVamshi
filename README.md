# Sentiment Analysis on Product Reviews

## 📌 Project Overview

This project performs Sentiment Analysis on Amazon Fine Food Reviews using Natural Language Processing (NLP). The goal is to classify customer reviews as Positive, Negative, or Neutral and generate meaningful insights from customer feedback.

## 🎯 Objective

To analyze customer reviews and understand customer sentiment by applying TextBlob sentiment analysis. The project helps identify customer satisfaction levels and provides actionable business recommendations based on review data.

## 📂 Dataset

Dataset Used: Amazon Fine Food Reviews

Source:
https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

For this project, only the first 5,000 reviews were used as per the assignment requirements.

## 🛠️ Technologies Used

- Python
- Pandas
- TextBlob
- Matplotlib
- Jupyter Notebook / Google Colab

## 📋 Project Workflow

### 1. Data Loading & Exploration
- Loaded the dataset using Pandas
- Displayed the first 10 rows
- Checked dataset dimensions
- Identified review text and rating columns

### 2. Data Cleaning
- Removed missing review texts
- Removed duplicate reviews
- Selected only required columns

### 3. Sentiment Analysis
- Calculated sentiment polarity using TextBlob
- Classified reviews as:
  - Positive (Polarity > 0)
  - Negative (Polarity < 0)
  - Neutral (Polarity = 0)

### 4. Data Visualization
Created three visualizations:
- Sentiment Distribution Bar Chart
- Sentiment Percentage Pie Chart
- Rating vs Sentiment Comparison Chart

### 5. Insights
- Positive Reviews: 88.34%
- Most customers expressed satisfaction with product quality, taste, freshness, and value.
- Negative reviews mainly highlighted packaging issues, delivery delays, and product quality inconsistencies.

## 📊 Results

The sentiment analysis revealed that 88.34% of reviews were positive, indicating a high level of customer satisfaction. The findings suggest that customers generally have a favorable perception of the products.

## 💡 Recommendation

The business should continue maintaining product quality while focusing on improving packaging and delivery processes to further enhance customer satisfaction and brand loyalty.

## 📁 Project Structure

```
SentimentAnalysis_BVamshi
│
├── analysis.ipynb
├── Reviews.csv
├── summary.pdf
│
└── charts
    ├── sentiment_bar.png
    ├── sentiment_pie.png
    └── custom_chart.png
```

## 🚀 Author

B VAMSHI

Week 1 Internship Project
