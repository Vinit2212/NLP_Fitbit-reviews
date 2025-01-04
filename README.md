# Fitbit Comments Sentiment Analysis

## Overview
This project leverages **Natural Language Processing (NLP)** to analyze customer reviews of Fitbit products. By extracting sentiment from user feedback, it uncovers key insights and identifies areas for improvement to enhance user satisfaction and experience.

---

## Features
- **Web Scraping**: Collected over 900 comments from Fitbit's community website using Selenium.
- **Sentiment Analysis**: Classified comments as positive, negative, or neutral using TextBlob.
- **Data Visualization**: Presented insights through bar charts, pie charts, and sentiment trends over time.
- **Actionable Insights**: Identified critical areas for improvement and praised features.

---

## Technologies Used
- **Programming Language**: Python  
- **Libraries**:
  - [Selenium](https://selenium.dev): Web scraping automation.
  - [Pandas](https://pandas.pydata.org/): Data manipulation and cleaning.
  - [NLTK](https://www.nltk.org/): Text preprocessing (cleaning, tokenization, lemmatization).
  - [TextBlob](https://textblob.readthedocs.io/): Sentiment classification using polarity scores.
  - [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/): Data visualization.

---

## Project Workflow

### 1. Data Collection
- Extracted 900+ comments from Fitbit’s community product pages using Selenium.
- Utilized Chrome WebDriver for automated data scraping.

### 2. Data Preprocessing
- Cleaned text by removing special characters, stopwords, and noise.
- Tokenized and lemmatized the comments for consistent analysis.

### 3. Sentiment Analysis
- **Polarity Scores** (assigned by TextBlob):
  - **Positive**: Polarity > 0  
  - **Negative**: Polarity < 0  
  - **Neutral**: Polarity = 0  

### 4. Data Visualization
- **Bar Charts**: Sentiment distribution.  
- **Pie Charts**: Proportions of positive, negative, and neutral comments.  
- **Trends**: Sentiment changes over time.

### 5. Insights
- **Negative Feedback**:
  - Missing features from the web dashboard.
  - Delayed exercise notifications.
  - Issues with sleep tracking accuracy.
- **Positive Feedback**:
  - Accurate activity tracking.
  - User-friendly interface.

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
