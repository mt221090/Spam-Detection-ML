# Spam-Detection-ML
STML Final Project WS 2023/24

### Task:
The primary task involves creating an AI model capable of distinguishing between spam and non-spam (ham) SMS messages. By utilizing the SMS Spam Collection Dataset, our goal is to develop, train, and evaluate machine learning models tailored for this specific purpose.

This endeavor encompasses crucial stages, starting with exploring and understanding the dataset. Cleaning the data by handling missing values, removing unnecessary elements, and executing text preprocessing tasks will be essential for model training.

Subsequently, we'll transform the text data into numerical features suitable for model training using techniques like TF-IDF or CountVectorizer.

The heart of this task lies in constructing machine learning models like Logistic Regression, Naive Bayes, SVM, Random Forest, and Gradient Boosting for accurate classification.

We'll rigorously evaluate these models using metrics such as accuracy, precision, recall, and F1-score, aiming to select the most efficient one.

### Problem Statement:
Develop an automated system that can accurately classify incoming SMS messages as either spam or legitimate (ham) based on their content.

### Research Question
What impact do text pre-processing methods have on the performance of SMS spam classification models with SMS spam collection Dataset?


## Discussion & Conclusion
According to the performance measurement, the best preprocessing methods are WordNertLemmentazier/No Preprocessing together with Support Vector classifier model.

Text preprocessing can make a huge difference depending on the data and use-case. In our case preprocessing has no impact or made it worse.

In some cases, the trained model has high score values but the confusion matrix shows that the model does not detect spam messages. The reason for that is that the dataset is unbalanced. In the dataset there are 87% ham messages and only 13% are spam messages.

According to the analysis made width LIME the words that indicate ham and spam are the following:

**ham**
- good
- he
- but
- thing
- not
- it
- do
- want

**spam**
- now
- to
- service
- call
- over
- free
- win
- until


## Links
Original Dataset: [https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/data](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/data)

Github Repository: [https://github.com/mt221090/Spam-Detection-ML](https://github.com/mt221090/Spam-Detection-ML)
