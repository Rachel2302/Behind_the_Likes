# YouTube Video Comment Sentiment

Introduction:
YouTube has over 2.5 billion monthly active users, making it the second largest social media/entertainment platform in the world after Facebook. Users upload over 500 hours of video content on YouTube every minute, providing a vast amount of information to analyze. Analyzing user behavior on certain YouTube channels (such as likes, comments, tags, and video titles) can provide insights into how viewers perceive the content and what changes can be made to improve it. During the COVID-19 pandemic, YouTube viewing traffic increased significantly due to restrictions forcing people to stay at home. The extended viewing time generated a large user base and revenue, motivating many people to pursue YouTube as a career option.

## Problem Statement
Sentiment analysis is crucial for understanding user engagement on YouTube
YouTube is a significant source of user-generated content and opinions
Analyzing the sentiment of YouTube comments can be challenging due to the large amount of data
Manual research can be time-consuming and inefficient
Determining the sentiment of comments that use sarcasm or irony can be difficult
An automated system is needed to efficiently and accurately analyze the sentiment of YouTube comments
Such a system would enable researchers to gather valuable insights into public opinion and user engagement on the platform
Data-driven decisions and effective strategies can be developed based on these insights

## Libraries Used
googleapiclient.discovery: Google API client library to access various Google APIs, such as Google Sheets or Google Drive.

pandas: A powerful data manipulation and analysis library, providing data structures like DataFrames and Series.

os: A module for interacting with the operating system, like reading from or writing to the file system.

numpy: A library for working with numerical data, supporting arrays, matrices, and various mathematical functions.

Json: A library for working with data in JavaScript Object Notation (JSON) format.Statistics: A library for performing statistical operations and calculations in Python.

Itertools: A library for creating and manipulating iterators and iterable objects in Python.Time: A library for working with dates, times, and time intervals in Python, 
including functions for measuring and benchmarking execution times.

## Data visualization packages:
seaborn: A statistical data visualization library built on Matplotlib that provides a high-level interface for drawing informative and attractive graphs.

matplotlib.pyplot: A plotting library for creating static, animated, and interactive visualizations in Python.

matplotlib.ticker: A module for customizing tick locators and formatters in Matplotlib plots.

## NLP Packages Used
nltk: A library for working with human language data (text), providing tools for text processing, classification, tokenization, stemming, tagging, and parsing.

nltk.corpus.stopwords: A module containing a list of common words that can be filtered out when processing natural language data.

nltk.tokenize: A module for breaking up text into words, phrases, symbols, or other meaningful elements (tokens).

wordcloud: A library for creating word cloud visualizations from text data.

Keras: A library used for artificial neural networks and as a prerequisite for TensorFlow.

## User-Defined-Functions:
Extractcomments(ec): Extracts comments from each videos.

Sentiment_vader(sv): Calculates sentiment score for each comment.

Visualizations(vis): Plots visualizations.

Getvideoids(fid): Gets video id for each video.

Getvideostatistics(vs): Gets statistics such as likes, comments for each video.

Predictionmodels(pred): Predicts like or dislike ratio using vader polarity score & defines baseline vader model; we also use linear regression.

Createtimeseriesdata(ctsd): Grouped data using date.

Predictiontimeseriesmodel(ptsm): We use LSTM model to predict future sentiment using time series data.

