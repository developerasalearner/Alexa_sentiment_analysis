# Alexa_sentiment_analysis

This project focuses on sentiment analysis of Alexa reviews using two machine learning models: Multinomial Naive Bayes and LinearSVC. The goal is to predict the sentiment (positive or negative) of the reviews based on the text content.

# Dataset:
The dataset used for this project consists of a collection of customer reviews for Alexa, a popular virtual assistant developed by Amazon. The dataset includes text reviews along with their corresponding sentiment labels (positive or negative). The dataset was preprocessed to remove noise and irrelevant information, ensuring that the models focus on the essential aspects of the reviews.

# Models:
Two different models were implemented and evaluated for sentiment classification:

1. Multinomial Naive Bayes: This model is a probabilistic classifier based on Bayes' theorem. It assumes that the features are conditionally independent given the class. The Multinomial Naive Bayes algorithm was chosen for its simplicity and effectiveness in handling text data.

Accuracy: 87.30%
2. LinearSVC (Support Vector Classifier): This model uses support vectors to create a decision boundary that separates the positive and negative sentiment classes. LinearSVC was selected due to its ability to handle high-dimensional data and its robustness against overfitting.

Accuracy: 93.65%

# Results and Evaluation:
Both models achieved promising results in sentiment classification, with the LinearSVC model outperforming the Multinomial Naive Bayes model in terms of accuracy. The higher accuracy of the LinearSVC model suggests that it can better capture the complexities and nuances of the Alexa reviews.

To evaluate the models, the dataset was split into training and testing sets. The models were trained on the training set and evaluated on the testing set using accuracy as the performance metric. The accuracy measures how often the models predicted the correct sentiment label for a given review.

# Conclusion:
This project demonstrates the application of two machine learning models, Multinomial Naive Bayes and LinearSVC, for sentiment analysis of Alexa reviews. By achieving high accuracy rates, the models provide valuable insights into the sentiment of customer reviews, which can be beneficial for improving the Alexa virtual assistant.

Feel free to explore the code, experiment with different models or datasets, and contribute to further enhancements of this sentiment analysis project. If you have any questions or suggestions, please don't hesitate to reach out.

Happy sentiment analysis!
