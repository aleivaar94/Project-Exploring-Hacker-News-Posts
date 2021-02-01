# Exploring Hacker News Posts
Explore and analyse "Ask HN" and "Show HN" posts in the Hacker News site.

## Context

Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. We are interested in posts whose titles begin with either Ask HN or Show HN. Users submit Ask HN posts to ask the Hacker News community a specific question. Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting. For example:


* Ask HN: How to improve my personal website?
* Show HN: Shanhu.io, a programming playground powered by e8vm


## Objective

The objective of this project is to explore and analyse Ask and Show HN posts using Python to answer the following questions:


* Do Ask HN or Show HN receive more comments on average?
* Do posts created at a certain time receive more comments on average?

## Approach

**1. Data Collection**
* Data is sourced from Dataquest.

**2. Opening and Exploring the Data**
* Data is opened and explored as a list of lists.

**3. Extracting Ask HN and Show HN Posts**
* Posts will be extracted in independent lists using string methods to identify how they start. Ask HN posts start with "Ask HN", Show HN posts start with "Show HN."

**4. Calculating the Average Number of Comments for Ask HN and Show HN Posts**
* Extract the number of comments using a For Loop and adding each number of comments to independent variables.

**5. Calculating the Average Number of Comments per Hours**
* Extract the time stamp and number of comments using a For Loop and adding each to a list.
* Transform to datetime format using the datetime module and count the hours using a For Loop and dictionaries.


## Results
Based on the analysis, to maximize the amount of comments a post receives, we'd recommend the post be categorized as ask post and created between 15:00 and 16:00 (3:00 pm - 4:00 pm EST).
