# Airbnb Sentiment Analysis

Customers can leave reviews for the rented space and sometimes bad ones can scare people away.

We'll analyze how's the review looks like, from Airbnb public data.

Using Python 3 and some popular libraries. 
[nltk](https://www.nltk.org/), [matplotlib](https://matplotlib.org/) , [pandas](https://pandas.pydata.org/)


## Business Understanding

Bad review could turn customers away.

It's now common for a customer to do their own research before deciding a buy. 
Some aspects they like to compare are price, product review, brand, etc. 
During their own research, consumer able to look for positive or negative reviews.


A study founds that online reviews affect [67%](https://soundwave.co.uk/blog/study-finds-67-of-consumers-are-influenced-by-online-reviews) of consumer purchasing decision. 
Positive reviews would increase the reputation, and able to drive more sales. 
Meanwhile, negative reviews could be detrimental to business. Revenue Loss, Undermine brand image, drive away customer visit, and low search traffic.

Thus, it's essential for the business to find bad review and take action to improve the product/service

These are the questions that we wish to answer in this analysis : 
- How to identify positive and negative reviews? 
- What are the popular words from the customers? 
- How to detect negative reviews and does it robust enough to detect the sentiment?


## Project Motivation

This project intend to look Airbnb review sentiment in Denver, Colorado (USA). 

Here's the question I'm aiming to look :

1. How is the rating distribution between cities ? 
2. What are the most frequent words used in reviews ?
3. How is the performance of sentiment analysis in the reviews ?
4. Does the sentiment analysis able to classify sentiments ?

The data was collected by Inside Airbnb
(http://insideairbnb.com) and made available under a Creative Commons license.


## Data Understanding

The data taken from Inside Airbnb (http://insideairbnb.com) for the city of Denver, CO
- denver_listings : Contains the description of review and ratings

- denver_reviews: contains ID for reviewer and comments 
    
First, we will find the overall rating of the service and find the popular review words.

Then we will use the sentiment analysis to find bad reviews

The sentiment analysis uses NLTK, which is a powerful language tool to analyze text data. 


## Results:

- Airbnb has a pleasant experience when using the service, the ratings were ±90%

- Reviews have missing values and treated with filling in blanks

- Data cleaning with removing stopwords is essential to find the most frequent word

- NLTK able to classify the sentiment category well enough. But, sometimes would need human assistance to improve its accuracy in a fraction of cases

- Business should take action for the bad review from the negative score and reading customers' complaints. 

- For future research, we need to compare other datasets that have mixed reviews.
