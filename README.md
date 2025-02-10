```markdown
# Google Play Store Apps and Reviews Analysis

## Overview
This project analyzes over ten thousand apps from the Google Play Store. The goal is to uncover insights into the Android app market by comparing app categories, ratings, pricing strategies, and user sentiments. This analysis can help developers and businesses devise strategies to drive growth and retention.

## Dataset
The project uses two datasets:
1. **apps.csv** - Contains details of applications on Google Play with 13 features.
2. **user_reviews.csv** - Contains 100 reviews for each app, including sentiment analysis (Positive, Negative, or Neutral), sentiment polarity, and sentiment subjectivity.

## Key Analyses
### 1. Data Cleaning
- Removal of special characters (e.g., `$`, `+`, `,`) from `Installs` and `Price` columns.
- Converting `Installs` and `Price` to appropriate numeric data types.
- Summary statistics generated using `info()`.

### 2. Exploring App Categories
- Identification of the most prevalent app categories.
- Analysis of market share for each category.
- Insights on underrepresented app categories.

### 3. Distribution of App Ratings
- Examination of the average app rating (4.17 overall).
- Distribution analysis showing the majority of apps are highly rated.

### 4. Size and Price Analysis
- Correlation between app size and ratings.
- Impact of app pricing on user preferences.
- Majority of top-rated apps are between 2MB to 20MB in size.
- Most apps are priced under $10.

### 5. Category-Wise Pricing Trends
- Identification of high-priced categories (e.g., Medical apps reaching $80).
- Analysis of pricing strategies based on app category and user demand.

### 6. Filtering Out Junk Apps
- Removal of overpriced and low-value apps from the dataset.
- Improved visualization of valid apps.

### 7. Popularity of Free vs Paid Apps
- Comparison of installs between free and paid apps.
- Finding that free apps have significantly higher installs than paid apps.

### 8. Sentiment Analysis of User Reviews
- Mining user reviews to determine sentiment (positive, negative, neutral).
- Free apps receive more negative reviews compared to paid apps.
- Paid apps generally have higher sentiment polarity, indicating better quality.

## Tools and Technologies Used
- **Python** (Pandas, Matplotlib, Seaborn, Plotly, NLTK)
- **Jupyter Notebook** for analysis
- **Data Cleaning and Preprocessing** techniques
- **Sentiment Analysis** using Natural Language Processing

## Conclusion
This project provides valuable insights into Google Play Store apps, their market trends, and user perceptions. The findings can guide developers in making data-driven decisions regarding app pricing, size optimization, and category selection.

## How to Use
1. Clone the repository.
2. Open `notebook.ipynb` in Jupyter Notebook.
3. Run each cell sequentially to perform the analysis.

## Future Enhancements
- Extend sentiment analysis with deep learning techniques.
- Perform time-series analysis to study app performance over time.
- Incorporate additional features like user demographics.

---
This README provides an overview of the project and its findings. For more details, refer to the Jupyter Notebook.
```

