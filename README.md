# ChatGPT Review Analysis

## Project Overview

This project provides a comprehensive analysis of over 190,000 user reviews for the ChatGPT application. The objective is to perform sentiment analysis and feature extraction to understand user satisfaction, identify key feedback patterns, and uncover actionable insights that can guide product improvements. The analysis covers the overall emotional tone of reviews, the specific aspects users praise or criticize, and how these trends evolve over time.

## Key Features & Analysis

* **Data Cleaning:** Preprocessed and cleaned the raw review data by standardizing column names, handling missing values, and correcting data types for analysis.
* **Sentiment Analysis:**
    * Calculated sentiment **polarity** and **subjectivity** for each review using the `TextBlob` library.
    * Categorized reviews into **Positive**, **Negative**, and **Neutral** buckets based on their polarity scores.
* **Feature & Keyword Extraction:**
    * Identified the most common phrases (bigrams and trigrams) from positive and negative reviews to pinpoint specific user feedback.
    * Categorized negative reviews into themes like `Performance`, `Accuracy`, `User Experience`, `Features`, and `Subscription` based on keyword analysis.
    * Analyzed neutral reviews to differentiate between truly neutral comments, questions, and feature requests.
* **Temporal Analysis:**
    * Tracked the volume of reviews over time to identify trends in user engagement.
    * Visualized how the distribution of positive, negative, and neutral sentiments has evolved on a monthly basis.
* **Data Visualization:** Created a series of plots using Matplotlib and Seaborn to effectively communicate the findings, including bar charts, histograms, and line graphs.

## Technology Stack

* **Language:** Python
* **Libraries:**
    * Pandas for data manipulation and analysis.
    * TextBlob for sentiment analysis.
    * Matplotlib & Seaborn for data visualization.
    * re (Regular Expressions) for text cleaning.
    * Collections (Counter) for frequency analysis.

## Key Insights

1.  **Overwhelmingly Positive Sentiment:** The analysis shows that the vast majority of user reviews are positive, which correlates strongly with high user ratings.
    
2.  **Praised Features:** Positive reviews frequently mention that the app is **"good"**, **"nice"**, and **"very helpful"**, highlighting user satisfaction with its core functionality and utility.
    
3.  **Actionable Negative Feedback:** The most common complaints from negative reviews relate to **Accuracy** (incorrect answers), followed by **Performance** issues (bugs, slow speed), and the **Subscription** model.
    
4.  **Value in Neutral Reviews:** A significant portion of neutral reviews are not just indifferent but contain valuable feedback like **Feature Requests** and **Questions** about the app's functionality.

