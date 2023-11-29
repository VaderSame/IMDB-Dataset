# Movie Review Sentiment Analysis

## Overview

The Movie Review Sentiment Analysis project aims to predict the sentiment (positive or negative) of movie reviews using natural language processing techniques. The dataset used for this project is the IMDb dataset, which consists of 25,000 movie reviews for binary sentiment classification. It includes 12,500 reviews for training and 12,500 for testing.

**Dataset Source:** [IMDb Movie Reviews Dataset](http://ai.stanford.edu/~amaas/data/sentiment/)

## Project Goal

The primary goal of this project is to build a classification model to predict whether a movie review is positive or negative based on its textual content. The project involves several key steps, including data preprocessing, feature engineering, model training, and evaluation.

## Implementation Steps

1. **Preprocess Text Data:**
   - Remove punctuation from the text.
   - Perform tokenization to break down the text into individual words.
   - Remove stopwords to eliminate common words that do not contribute much to the sentiment.
   - Lemmatize or stem words to reduce them to their base or root form.

2. **TFIDF Vectorization:**
   - Convert the preprocessed text data into numerical vectors using TFIDF (Term Frequency-Inverse Document Frequency) vectorization. This step transforms the text data into a format suitable for machine learning models.

3. **Exploratory Data Analysis (EDA):**
   - Explore the dataset to gain insights into the distribution of positive and negative reviews.
   - Visualize key features of the dataset to better understand the characteristics of the movie reviews.

4. **Model Training:**
   - Use machine learning models, specifically Random Forest and Gradient Boosting Classifier, for sentiment classification.
   - Explore various parameter settings for the models.

5. **GridSearchCV:**
   - Utilize GridSearchCV for hyperparameter tuning to find the best combination of parameters for Random Forest and Gradient Boosting Classifier.

6. **Model Evaluation:**
   - Evaluate the models using the best parameter settings.
   - Use appropriate evaluation metrics to assess the model's performance, such as accuracy, precision, recall, and F1-score.

7. **Report the Best-Performing Model:**
   - Summarize and report the findings, including the best-performing model and its corresponding parameter settings.
   - Discuss the implications of the results and potential areas for improvement.

## Getting Started

To replicate the analysis and results, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/VaderSame/IMDB-Dataset.git

## Notes

- Make sure to check the Jupyter notebooks for detailed explanations of each step.
- Feel free to modify the code to suit your specific requirements.

## Author

[Semal Shastri]

## License

This project is licensed under the [MIT License](LICENSE).
   
