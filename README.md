# Airbnb Sentiment Analysis

Customers can leave reviews for the rented space and sometimes bad ones can scare people away.

We'll analyze what the reviews look like, from Airbnb's public data.

Using Python 3 and some popular libraries. 
[nltk](https://www.nltk.org/), [matplotlib](https://matplotlib.org/) , [pandas](https://pandas.pydata.org/)




## Business Understanding

Bad reviews could turn customers away.

It's now common for a customer to do their research before deciding to buy. 
Some aspects they like to compare are price, product review, brand, etc. 
During their research, consumers can look for positive or negative reviews.


A study found that online reviews affect [67%](https://soundwave.co.uk/blog/study-finds-67-of-consumers-are-influenced-by-online-reviews) of consumer purchasing decisions. 
Positive reviews would increase the reputation, and able to drive more sales. 
Meanwhile, negative reviews could be detrimental to business. Revenue Loss, Undermine brand image, drive away customer visits, and low search traffic.

Thus, the business needs to find bad reviews and take action to improve the product/service

These are the questions that we wish to answer in this analysis : 
- How to identify positive and negative reviews? 
- What are the popular words from the customers? 
- How to detect negative reviews and is it robust enough to detect the sentiment?




## Project Motivation

This project intends to look at Airbnb review sentiment in Denver, Colorado (USA). 

Here's the question I'm aiming to look at:

1. How is the rating across properties in Denver? 
2. What are the most frequent words used in reviews?
3. How is the performance of sentiment analysis in the reviews?
4. Is the sentiment analysis able to classify sentiments?

The data was collected by Inside Airbnb
(http://insideairbnb.com) and made available under a Creative Commons license.




## Data Understanding

The data are taken from Inside Airbnb (http://insideairbnb.com) for the city of Denver, CO
- denver_listings: Contains the description of review and ratings

- denver_reviews: contains ID for reviewer and comments 
    
First, we will find the overall rating of the service and find the popular review words.

Then we will use Sentiment Analysis to find bad reviews

The sentiment analysis uses NLTK, which is a powerful language tool to analyze text data. 




## Results:

- Airbnb has a pleasant experience when using the service, the ratings were ±90%

- Reviews have missing values and are treated with filling-in-blanks

- Data cleaning with removing stopwords is essential to find the most frequent word

- NLTK can classify the sentiment category well enough. But, sometimes would need human assistance to improve its accuracy in a fraction of cases

- Businesses should take action for the bad reviews from the negative score and read customers' complaints. 

- For future research, we need to compare other datasets that have mixed reviews.
