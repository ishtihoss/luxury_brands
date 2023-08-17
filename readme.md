# Luxury Brands Sentiment Analysis

## Overview

This project analyzes the sentiment around various luxury brands using news headlines collected from Google News. The analysis covers the period from September 2022 to August 2023, capturing the trends and sentiments associated with brands like Gucci, Prada, Tom Ford, Versace, and others.

### Data Collection

The data was collected by scraping Google News using BeautifulSoup. The search query was crafted for each brand, focusing on news articles from the past year. The collected data includes:

- **Date**: The publication date of the news article.
- **Source**: The source of the news article.
- **Headline**: The headline text of the news article.
- **Brand**: The brand associated with the news article.

### Analysis

#### Sentiment Analysis

The project employs the Hugging Face Transformers library to perform sentiment analysis on the collected headlines. The sentiments were categorized as positive, neutral, or negative, allowing for an in-depth understanding of public perception.

#### Time Series Visualization

The analysis includes time series visualizations to depict:

- **News Mentions**: A line plot showing the weekly count of news mentions for each brand.
- **Sentiment Over Time**: A line plot representing the sentiment trend for each brand over time.

#### Word Clouds

The project also incorporates word cloud visualizations to highlight the most frequently occurring words in the headlines for each brand, excluding common stopwords and the brand names themselves.

### Libraries and Tools

The project utilizes the following libraries and tools:

- pandas
- matplotlib
- seaborn
- BeautifulSoup
- requests
- Hugging Face Transformers
- wordcloud
- numpy

### Author

- **MD Ishtiaque Hossain AKA Ishti**

