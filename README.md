# <img src="https://img.icons8.com/color/48/000000/document.png"/> <img src="https://img.icons8.com/fluent/48/000000/twitter.png"/> Sentiment Analysis on Twitter Data

This project involves using natural language processing techniques to conduct binary sentiment classification on a dataset comprising tweets. The objective is to categorize each tweet as either positive or negative based on the sentiment conveyed in the text.

## <img src="https://img.icons8.com/color/48/000000/database.png"/> Dataset

The Sentiment140 dataset with 1.6 million tweets was used for this project. The dataset was preprocessed and cleaned to remove URLs, special characters, and stop words.

Dataset source :- https://www.kaggle.com/datasets/kazanova/sentiment140

## <img src="https://img.icons8.com/color/48/000000/brain.png"/> Methodology

Two models, logistic regression and LSTM, were selected for sentiment analysis. Logistic regression, a well-established and interpretable model, was deemed appropriate for straightforward sentiment analysis tasks. In contrast, LSTM, a recurrent neural network variant, excelled in capturing sequential dependencies within textual data.

The models were trained and tested on a subset of the original dataset using several evaluation metrics, including accuracy, precision, recall, and F1-score. These metrics provide insights into how well the models perform in correctly classifying positive and negative sentiment in tweets.

## <img src="https://img.icons8.com/color/48/000000/analytics.png"/> Results

The LSTM model demonstrated slightly superior performance across all evaluation metrics, exhibiting marginally higher accuracy, precision, recall, and F1-score. These findings underscore the potential real-world implications of the LSTM model, making it a favorable choice for sentiment analysis endeavors.

## <img src="https://img.icons8.com/color/48/000000/settings.png"/>  Tools

The following tools were used in this project:

- Python 3.7.3 <img src="https://img.icons8.com/color/48/000000/python.png"/>
- TensorFlow 2.1.0 <img src="https://img.icons8.com/color/48/000000/tensorflow.png"/>
- NumPy 1.18.4 <img src="https://img.icons8.com/color/48/000000/numpy.png"/>
- Pandas 1.0.3 <img src="https://img.icons8.com/color/48/000000/pandas.png"/>
- Scikit-learn 0.22.2 
- Jupyter notebook 6.0.3


## <img src="https://img.icons8.com/material-outlined/48/000000/click.png"/> Usage
To use this code, clone the repository and run the Jupyter notebook in a Python environment with the required packages installed. The notebook includes detailed explanations of the code and the methodology used.

## <img src="https://img.icons8.com/color/48/000000/conference-call.png"/> Authors

This project was created by the following team members as a part of King Saud University's research on sentiment analysis:

- Hutoon AlOmran
- Lena AlSuwailem
- Razan AlDhafian
- Noura AlSultan
- Nouf AlFulaij
- Seba AlAhmadi
