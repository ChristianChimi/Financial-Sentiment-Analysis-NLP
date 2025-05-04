## **Financial Sentiment Analytics - NLP**
## **Overview**
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
    - Frequent Words per Sentiment
        - Most common words in each class identified
        - Stopwords (e.g., "the", "and", "is") were removed to focus on more meaningful tokens, providing clearer insights into the content of the sentences and improving the accuracy of the sentiment model.

## **Key insights**
    - Sentence Length: Positive sentences tend to be slightly longer than negative ones, suggesting that more elaborate or detailed content may be associated with positive sentiment in financial text.
    - Common Words: Analysis of the most frequent words in each sentiment class revealed distinct patterns, with positive sentiment sentences often containing more optimistic or growth-related terms.
    - Model Performance: The classification model showed a solid ability to predict sentiment, with metrics such as accuracy, precision, recall, and F1-score providing a balanced view of its effectiveness in distinguishing between positive and negative sentiment.

## **Conclusions**
This project demonstrates how Natural Language Processing (NLP) can be leveraged to analyze financial text data and classify sentiment effectively. By training a machine learning model on labeled data, we were able to classify sentences as either positive or negative, offering valuable insights for applications like market sentiment analysis or customer feedback analysis. The project also highlighted the importance of text features, such as sentence length and common word usage, in improving sentiment classification accuracy. Overall, NLP techniques are powerful tools for understanding financial sentiment, providing businesses and analysts with actionable insights.

## **Technologies Used**
 - **Python**, **Pandas**, **Numpy**, **Scikit-learn**, **Nltk**
