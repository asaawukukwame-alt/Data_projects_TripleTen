# Movie Review Sentiment Classification — Film Junky Union

## Project Description

This project focused on building a natural language processing model to classify movie reviews as positive or negative. The goal was to help automate review filtering and sentiment analysis for a movie review platform.

## Objective

The objective was to train a classification model that could detect negative movie reviews with strong F1 score performance.

## Tools and Technologies

- Python
- pandas
- NumPy
- scikit-learn
- NLTK
- Regular Expressions
- TF-IDF
- Bag-of-Words
- Logistic Regression
- Classification Models
- F1 Score
- Jupyter Notebook

## Methods

The project included the following steps:

1. Loaded and reviewed the movie review dataset.
2. Checked the class balance between positive and negative reviews.
3. Cleaned and normalized text data.
4. Applied lowercasing, regular expressions, tokenization, stopword handling, and lemmatization.
5. Converted text into numerical features using Bag-of-Words and TF-IDF.
6. Trained and compared multiple classification models.
7. Evaluated model performance using F1 score.
8. Tested the models on custom-written movie reviews.

## Results

The project demonstrated how NLP models can classify review sentiment using cleaned text and vectorized features. Model performance was evaluated using F1 score to balance precision and recall.

## Business Value

This type of model can help platforms automatically identify negative reviews, monitor customer sentiment, organize content, and support moderation or recommendation systems.

## Future Improvements

- Test more advanced NLP models such as BERT or transformer-based models.
- Add more custom review examples for model testing.
- Improve preprocessing for sarcasm, slang, and complex review language.
- Build a simple web interface for live sentiment prediction.
