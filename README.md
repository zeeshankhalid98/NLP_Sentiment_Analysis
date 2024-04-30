# NLTK VADER Sentiment Analysis for Shakespeare’s Poems

This repository contains Python code demonstrating sentiment analysis using NLTK's VADER (Valence Aware Dictionary and sEntiment Reasoner) on a collection of Shakespeare's poems.

## Setup Instructions

To run the sentiment analysis on these poems, follow these steps:

1. **Use Google Colab:** Upload all five Shakespeare poems in the `sample_data` folder within your Google Colab environment. Be mindful of file names, especially avoiding characters like apostrophes (`'`) in file names due to potential issues with file paths.

2. **Install Dependencies:** Ensure you have the necessary libraries installed by running the following commands in your Colab notebook:


3. **Run the Code:** Copy and paste the provided Python code cells into your Colab notebook and execute them to perform sentiment analysis on the Shakespeare poems.

## Project Description

The goal of this project is to analyze the sentiment expressed in five Shakespearean poems using NLTK's VADER sentiment analysis tool. The sentiment analysis will calculate overall sentiment scores for each poem and rank them from most positive to most negative based on these scores.

## Results and Analysis

After running the sentiment analysis code, the poems are ranked based on their sentiment scores. A brief analysis is provided for each poem to explain the sentiment score in context.

### Feasibility of Statistical Methods

The sentiment analysis utilizes NLTK's `SentimentIntensityAnalyzer` to compute compound sentiment scores for each sentence and then calculates the average compound score for the overall sentiment. This method provides a feasible approach to gauge sentiment in literary texts.

### Extended Applications

Sentiment analysis techniques demonstrated in this assignment have broad applications:

- **Content Recommendation Systems:** Personalize content recommendations based on user sentiment.

- **Customer Feedback Analysis:** Gain insights from customer sentiments to improve products/services.

- **Market Research:** Analyze public sentiment towards brands and products for informed marketing strategies.

- **Literary and Cultural Studies:** Automate sentiment analysis of literary works to identify trends and themes over time.

These applications showcase the versatility of sentiment analysis in various domains, aiding decision-making and enhancing user experiences.
