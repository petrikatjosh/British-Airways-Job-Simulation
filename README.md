## Project Overview
This project analyzes 1,000 British Airways customer reviews sourced from the Skytrax website. Using TextBlob, each review was evaluated for:

Polarity → Measures how positive or negative the review is (range: -1 to 1)

Subjectivity → Measures how subjective or objective the review is (range: 0 to 1)

The analysis includes statistical summaries, visualizations, and a non-linear regression model to identify potential patterns in customer sentiment.

## Tools & Technologies
Python (Jupyter Notebook)

Pandas — Data handling

TextBlob — Sentiment analysis

Matplotlib / Seaborn — Visualization

Scikit-learn — Regression modeling

## Key Findings
Average Polarity: 0.0680 → Neutral sentiment (comparable to a 5/10 rating)

Average Subjectivity: 0.4879 → Balanced mix of objectivity and subjectivity

Scatterplots revealed a quadratic-like pattern:

Customers with extreme positive or negative opinions tend to be more subjective

Neutral reviewers tend to be more objective

A quadratic regression model was fitted to visualize this relationship.

## Acknowledgments
Skytrax for providing the review data

TextBlob for sentiment analysis tools

British Airways (dataset subject)
