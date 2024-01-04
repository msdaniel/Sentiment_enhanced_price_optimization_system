# Sentiment_enhanced_price_optimization_system

# Sentiment Analysis for Real-time Pricing Optimization in the Mexican Hotel Industry

## 1. Research Problem

The research problem addressed in this study is the limited understanding of the potential of sentiment analysis in optimizing pricing strategies in the Mexican hospitality industry. There is a gap in research exploring the specific impact of sentiment analysis on pricing decisions in the Mexican context, particularly within the unique dynamics of the hospitality industry.

## 1.1 Aim and Objectives

**Aim:**
Optimize hotel pricing strategies in real-time using customer sentiment analysis by developing a framework that integrates sentiment analysis results into pricing optimization models specific to the Mexican hospitality industry.

**Objectives:**
1. Collect and preprocess a large dataset of hotel reviews from various online review websites such as TripAdvisor and Booking.com.
2. Develop a sentiment analysis model using natural language processing and machine learning techniques.
3. Integrate the sentiment analysis model with a pricing optimization system to adjust hotel prices based on customer sentiment.
4. Evaluate the performance of the sentiment analysis model and the pricing optimization system through simulation experiments and statistical analysis to measure their impact on customer satisfaction and hotel revenue.

## 1.2 Research Questions

1. What are the most common themes and sentiments found in online reviews of hotels in Mexico?
2. How can sentiment analysis be used to adjust pricing in real-time based on customer sentiment?
3. How effective is sentiment analysis-based pricing optimization in improving revenue for hotels in Mexico?

## 1.3 Methodology

The methodology consists of three main components: data collection, sentiment analysis approach, and integration with pricing optimization models.

### Data Collection Process

- Gathered online review data from TripAdvisor and Booking.com using the Web Scraper Chrome extension.
- Extracted 3,741 reviews from 59 hotels on TripAdvisor and 7,700 reviews from 69 hotels on Booking.com, totaling 10,229 rows of reviews.
- Deliberately and systematically selected hotels across six cities in Mexico for regional diversity.

### Text Preprocessing

1. Converted review text to lowercase.
2. Expanded common contractions to avoid misinterpretations.
3. Removed punctuations, digits, and stopwords.
4. Removed unnecessary line breaks.

### Tokenization and Lemmatization

- Tokenized reviews into individual words or tokens.
- Lemmatized words to their base or root form.

### Sentiment Analysis

- Utilized sentiment lexicons specific to the hotel industry.
- Employed machine learning algorithms, including supervised learning techniques, to train sentiment classification models.

### Integration with Pricing Optimization Models

- Detected sentiments in reviews and translated them into numerical values (0 or 1).
- Incorporated sentiment scores into a collaborative filtering algorithm for real-time pricing decisions.

### Evaluation

- Conducted a comprehensive evaluation and validation process on the models.
- Ensured validity through statistical analysis and performance metrics of machine learning algorithms.

## 1.4 Scope

This project focuses specifically on the Mexican hotel industry, utilizing customer sentiment analysis for real-time pricing optimization. The study primarily employs online review data from platforms such as TripAdvisor and Booking.com, leveraging natural language processing techniques and machine learning algorithms for sentiment analysis.
