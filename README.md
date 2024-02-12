# Financial Analysis on Twitter

This repository hosts the code and datasets for conducting financial analysis on Twitter data. The dataset can be downloaded from [this link](https://zenodo.org/records/2686862). The project is divided into two parts.

**Part 1: Exploratory Data Analysis**

In this part, a dataset containing over 5 million tweets mentioning stocks traded in the US markets is provided. The dataset also includes basic user information and financial data on the mentioned stocks. The task is to perform thorough exploratory data analysis (EDA) to gain insights into the dataset. Deliverables for this part include:

- Statistics on the most and least tweeted stocks.
- Segmentation of companies based on tweet volume with relevant visualizations.
- Analysis of distributions of individual stocks over time.
- Analysis of distributions of all financial tweets over time.
- Analysis of distributions of retweets per tweets for selected stocks over time.
- Identification of most important financial information on selected stocks computed solely from financial data.
- Analysis of time series movement directions for selected stocks with real-world news explanations.
- Co-occurrence analysis of various stocks in the same tweets.

**Part 2: Sentiment Analysis**

In this part, sentiment analysis is performed on a labeled dataset of tweets. Steps involved in this part include:

- Data cleaning, including removal of duplicates and useless data.
- Feature extraction using bag of words and TF-IDF techniques.
- Training supervised algorithms on each set of features.
- Hyperparameter tuning and model selection.
- Utilizing pre-trained libraries like BERT or SpaCy for sentiment analysis.
- Optionally, constructing a classifier with ChatGPT API or HuggingFace models.
- Comparison of different methods and discussion of results.

Useful libraries for this project include TextBlob, NLTK, SpaCy, and OpenAI.
