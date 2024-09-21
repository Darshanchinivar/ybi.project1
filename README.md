# YBI Foundation Internship projects
# 1.Hand Written Digit Classification:
This project demonstrates a Handwritten Digit Prediction system using the Random Forest Classifier. The dataset consists of 8x8 pixel grayscale images of handwritten digits. After visualizing a few sample images, the data is preprocessed by reshaping and scaling the pixel values. The dataset is split into training and testing sets, followed by training a Random Forest Classifier on the training data. The model is evaluated using the test data, and the performance is measured with metrics like confusion matrix and classification report, achieving an accuracy of 98% in predicting the correct digits.
# 2.Financial market News Sentiment Analysis:
This project performs sentiment analysis on a financial market news dataset containing the top 25 news headlines per day, predicting whether the overall market sentiment is positive (1) or negative (0). The dataset is loaded using pandas, and exploratory analysis reveals 4101 rows and 27 columns (including a date, sentiment label, and 25 news headlines). The headlines are concatenated for each day to form a single text feature. A bag-of-words model is applied using CountVectorizer to convert the text data into numerical features. The dataset is then split into training and testing sets using train_test_split. A RandomForestClassifier with 200 estimators is trained on the data, and the model’s performance is evaluated using accuracy, confusion matrix, and classification report. The final model achieves an accuracy of 52%, with precision and recall metrics varying between the two sentiment classes.
# 3.Wine Quality Prediction Using Support Vector Machine:
This project is a Financial News Sentiment Analysis tool that analyzes daily financial news articles to gauge market sentiment. It processes a dataset of the top 25 financial articles per day using techniques such as TF-IDF vectorization for text representation and a Random Forest Classifier for sentiment prediction. The goal is to classify each article's sentiment as positive or negative, providing insights into market trends. The project leverages Python libraries such as Pandas, Scikit-learn, and NLTK for text processing and machine learning."
