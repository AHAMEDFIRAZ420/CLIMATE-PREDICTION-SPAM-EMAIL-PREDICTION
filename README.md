ML Exploration: Climate & Spam 

This repository is my personal playground for learning Machine Learning and Data Science. Instead of just reading theory, I wanted to build two simple, functional models that solve classic problems: predicting environmental trends and filtering digital noise.

Project 1: Climate Trend Predictor

A script that looks at historical temperature data to see where we might be heading.

The Goal: To explore how linear patterns emerge in long-term weather data.

The Approach: It seems to me that Regression is the perfect starting point for this. I used it to map the relationship between "Time" and "Global Temperature."

What I Learned: How to handle time-series data and visualize a "Line of Best Fit."


Project 2: Spam Email Filter

A simple Natural Language Processing (NLP) tool that decides if an email is "Ham" (good) or "Spam" (bad).

The Goal: To understand how a computer can "read" and categorize text.

The Approach: I used Tokenization and word frequency to find patterns—like how often the word "Winner" appears in spam vs. regular mail.

What I Learned: The importance of cleaning data (removing stop words and punctuation) before feeding it to a model.


How I Built It
I kept the stack lean and effective:

Python: The backbone of both scripts.

Pandas: For organizing the data into tables.

Scikit-Learn: For the actual "intelligence" (Regression and Classification).

Matplotlib: To turn numbers into readable charts.
