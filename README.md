# Sentiment-Analysis-NLP
Performing Sentiment Analysis on over 5000 user reviews for melatonin products sold online. 

# Melatonin Product Review Analysis

## Project Overview

This project analyzes user reviews of various melatonin products from Amazon, focusing on customer sentiment, common themes, and product effectiveness. The analysis includes data preprocessing, encoding, sentiment analysis, building word clouds and visualizations to identify patterns and insights from the reviews. By understanding user feedback, we draw conclusions about product satisfaction and identify areas for potential improvement.

## Dataset Overview

The dataset comprises reviews for products, each containing:
- **Product Information**: Title, brand, average rating, and total review count.
- **Review Details**: Reviewer ID, rating, review text, review header, and helpfulness votes.
- **Additional Metadata**: Verified purchase status, reviewer’s location, and specific product variants.

## Installation

### Prerequisites
To set up this project locally, ensure you have Python installed, preferably version 3.7 or higher.

### Required Libraries
Install the necessary Python libraries by running:

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn
import nltk
nltk.download('vader_lexicon')
nltk.download('stopwords')
nltk.download('punkt')

