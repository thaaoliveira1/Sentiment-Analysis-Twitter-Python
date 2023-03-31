# Twitter Sentiment Analysis

## Final Project Advanced Machine Learning

This dataset is from a 2014 survey that measures attitudes towards mental health and frequency of mental health disorders in the tech workplace. You are also encouraged to analyze data from the ongoing 2016 survey found here.

This project is a Twitter sentiment analysis application that uses machine learning algorithms to classify tweets as positive, negative, or neutral. It uses a dataset of pre-labeled tweets to train a machine learning model and then applies that model to classify new tweets in real-time.

### Requirements
To use this application, you will need to have the following installed on your machine:

Python 3.x
Jupyter Notebook
NumPy
Pandas
Scikit-learn
Tweepy
NLTK


### Getting Started
To get started with this application, follow these steps:

1. Clone this repository to your local machine.
2. Download the file from this link https://drive.google.com/file/d/1FAgZ9cdNjlousnXqvZ-36p0QIpb0tbm3/view?usp=share_link, copy it to the repository folder and rename it to `twitter_data.csv`
3. Install the required libraries listed in the requirements.txt file using the following command: pip install -r requirements.txt.
4. Obtain Twitter API credentials and update the config.py file with your credentials.
5. Open the Twitter_Sentiment_Analysis.ipynb file in Jupyter Notebook.
6. Follow the instructions in the notebook to train the machine learning model, apply it to classify new tweets, and analyze the results.

### Machine Learning Theory
This project is designed to showcase the application of machine learning algorithms to natural language processing tasks, such as sentiment analysis. In particular, the notebook demonstrates the use of a support vector machine (SVM) classifier and a naive Bayes classifier to classify tweets based on their sentiment.

The SVM classifier works by finding the hyperplane that maximally separates the different classes of data points in a high-dimensional space. The naive Bayes classifier, on the other hand, is a probabilistic algorithm that calculates the likelihood of each class given the features of the input data.

In addition to these classifiers, the notebook also explores techniques for preprocessing and feature engineering text data, such as tokenization, stemming, and the bag-of-words model.

### Acknowledgements
This project was inspired by the Sentiment140 dataset, which contains 1.6 million tweets that have been labeled as positive, negative, or neutral. The notebook also draws on examples and documentation from the scikit-learn and NLTK libraries.

## FAQ

### I did commit a huge file, what should I do? :(
- Run `git reset --hard HEAD~1` to delete de latest commit. If you did this more than once, run this command as many times as needed. You can check if you still have "broken" commits by running `git status`. As long as you see `Your branch is ahead of 'origin/main' by N commit.` it means you still aren't were you were supposed to be. The expected result should be `Everything up-to-date`. Also remember that every other changes you made on those commits will be lost, so backup them before doing this!
