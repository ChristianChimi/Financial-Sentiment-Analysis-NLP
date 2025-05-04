## **Financial Sentiment Analytics - NLP**
This project leverages Natural Language Processing (NLP) techniques to classify the sentiment of sentences into two categories: positive or negative. The model was trained on a labeled dataset containing sentences paired with their corresponding sentiment labels. The goal is to understand and classify the underlying sentiment in financial text data, which can be useful for applications such as market sentiment analysis or customer feedback analysis.

## **NLP**
    - The project follows a structured NLP workflow to train and evaluate the sentiment classification model:
    - Training the Classification Model:
        - A machine learning model (such as Logistic Regression, Naive Bayes, or Random Forest) was trained on the labeled dataset to learn the patterns and associations between the text and sentiment labels.
    - Sentiment Prediction:
        - After training, the model is capable of predicting the sentiment (positive or negative) of unseen input sentences.
    - Evaluation Metrics:
        - Accuracy: The proportion of correctly classified sentences.
        - Precision: The proportion of correctly predicted positive sentences out of all predicted positives.
        - Recall: The proportion of correctly predicted positive sentences out of all actual positive sentences.
        - F1-score: A harmonic mean of precision and recall, providing a balance between the two.

## **Exploratory Data Analytics (EDA)**
    - Text Length Analysis
        - Compared average number of words per sentence by sentiment class
        - Positive sentences were slightly longer on average compared to negative ones, which could offer insights into the structure of financial sentiment.
    - Frequent Words per Sentiment
        - Most common words in each class identified
        - Stopwords (e.g., "the", "and", "is") were removed to focus on more meaningful tokens, providing clearer insights into the content of the sentences and improving the accuracy of the sentiment model.

## **Technologies Used**
 - **Python**, **Pandas**, **Numpy**, **Scikit-learn**, **Nltk**
