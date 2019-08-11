# Political-Sentiment-Analysis
CSPB 3022 Classification Project - Political Text Analysis/Predictions Using Supervised Learning Methods
***

## Introduction:
This dataset contains the classification of partisan bias, audience, and goal based on politicians' social media. Total rows total ~5000 and the objective is to clean, organize, manipulate data contents to derive meaningful conclusions based on hypotheses and analysis. For the final project, I have chosen sentiment analysis classifying political bias provided texts (in this case tweets). That is, to assign categories to the collection of data (political messaging) in order to aid in more accurate predictions and analysis.
    
I chose this topic in particular, not because I'm fascinated with politics, but the harnessing power of social media and was curious to see how natural language processing (NLP) could computationally identify and categorize opinions expressed in the political messages to determine potential biases. 

Now that a multivariate analysis problem of interest has been identified, the outline of the project shall continue as follows:
1. Selecting Data Sources
2. Preprocess data; Cleaning and transforming data, as needed
3. Perform Exploratory Data Analysis (EDA)
4. Perform Classification

Additional tools used: Building basic Natural Language Toolkit (NLTK) modules; 
***

### Data Source:

The idea of crowdsourcing draws on "wisdom of the crowd" arguments where I used the CrowdFlower/Kaggle database to access the data set to be used for this project, titled, "Political Social Media Posts" (https://www.kaggle.com/crowdflower/political-social-media-posts/data). For project consideration, we will later delve deeper into selecting relevant words from the political messages to try and accurately predict meaning and predictions. 

This dataset contains the results from contributors analyzing thousands of social media messages from US Senators and other American politicians to classify its contents. Messages were broken down into audience (national or the tweeter’s constituency), bias (neutral/bipartisan, or biased/partisan), and finally tagged as the actual substance of the message itself (options ranged from informational, announcement of a media appearance, an attack on another candidate, etc.)
***

### Intent:
 
1. Explore, clean, and modify the political message dataset to determine meaningful relationships between certain words and message types as indictaed by qualified human assessors from varying social media posts.

2. Determine how certain words in tweets/posts are correlated with political messages using heatmap/wordcloud.

3. Tranform data and perform linear, logistic regression, or other classification methods -- Decision tree classifiers: applying Naive Bayes or Support Vector Machine based algorithms for supervised machine-learning assessment.

4. Determine which classification based method is the stronger predictor for political bias/alignments between Multinomial Naive Bayes (MNB) text classification and Support Vector Machine (SVM) machine learning algorithms.
***

## Installation:
Please install all necessary packages given in the import lines

TextBlob: textblob is the python library for processing textual data.
Install it using following pip command:
***

$ pip install textblob

Wordcloud: Word cloud object for generating and drawing.
Install it using following pip command:
***

$ pip install wordcloud
