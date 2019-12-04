# Part 1: Roundtable Lightning Talks

## Overview

In this section, you will be presenting three potential topics to your coursemates (and fellow well-wishers!) You will be presenting your findings in the form of an informal [lightning talk](https://en.wikipedia.org/wiki/Lightning_talk).

**You do not need to prepare slides for your talk.  Just be prepared to discuss it with your colleagues.**

## How to select a topic

You can think about selecting a topic (at least) two ways:

1. Start with an idea then look for potential data that could support that idea.
2. Look for interesting data then think about what problems could be solved with that data.

> Throughout the capstone process it will be very valuable if you *document as you go!*  Perhaps keep a project journal (hard copy, text file or digital notebook) describing your decisions and findings.  This is will be a useful reminder for "future you" (who tends to forget your past decisions), and it will also be useful fodder for generating your final report.

## What is a lightning talk?

For our purposes, a lightning talk is a talk lasting **no more than five minutes**, in which you will discuss the following about your three proposed projects:

1. What is your problem statement?  What will you actually be doing?
2. Who is your audience?  Why will they care?
3. What is your success metric?  How will you know if you are actually solving the problem in a useful way?
4. What is your data source?  What format is your data in?  How much cleaning and munging will be required?
5. What are potential challenges or obstacles and how will you mitigate them?
6. Is this a reasonable project given the time constraints that you have?

Time limits will be strictly enforced.

> Note that you *should not* prepare slides for your talk.  This will be verbal pitches with discussion.

## Recommendations for your lightning talk

Think about your talk as a short pitch.  It will be helpful to practice your talk beforehand!  Keep it short, succinct and to the point.

Bolded and capitalized for as much effect as possible:

**HAVE YOUR DATA IN HAND AS SOON AS POSSIBLE**

There is no penalty for having to switch topics or datasets in the middle of the project, provided that you can still deliver on the other portions of this work. However, if you can get the data in hand as soon as possible, you can prevent yourself a lot of extra work.

## Deliverables

Be prepared to discuss 3 potential topics with your peers.

## Useful Resources

- [How to Find the Data You Need](http://flowingdata.com/2009/10/01/30-resources-to-find-the-data-you-need/)
- [16 Ways to Prepare for a Lightning Talk](https://www.semrush.com/blog/16-ways-to-prepare-for-a-lightning-talk/)
## [Google Datasets Search Tool](https://toolbox.google.com/datasetsearch)

# Part 1: Roundtable Lightning Talks

## Overview

In this section, you will be presenting three potential topics to your coursemates (and fellow well-wishers!) You will be presenting your findings in the form of an informal [lightning talk](https://en.wikipedia.org/wiki/Lightning_talk).

**You do not need to prepare slides for your talk.  Just be prepared to discuss it with your colleagues.**

## How to select a topic

You can think about selecting a topic (at least) two ways:

1. Start with an idea then look for potential data that could support that idea.
2. Look for interesting data then think about what problems could be solved with that data.

> Throughout the capstone process it will be very valuable if you *document as you go!*  Perhaps keep a project journal (hard copy, text file or digital notebook) describing your decisions and findings.  This is will be a useful reminder for "future you" (who tends to forget your past decisions), and it will also be useful fodder for generating your final report.

## What is a lightning talk?

For our purposes, a lightning talk is a talk lasting **no more than five minutes**, in which you will discuss the following about your three proposed projects:

1. What is your problem statement?  What will you actually be doing?
2. Who is your audience?  Why will they care?
3. What is your success metric?  How will you know if you are actually solving the problem in a useful way?
4. What is your data source?  What format is your data in?  How much cleaning and munging will be required?
5. What are potential challenges or obstacles and how will you mitigate them?
6. Is this a reasonable project given the time constraints that you have?

Time limits will be strictly enforced.

> Note that you *should not* prepare slides for your talk.  This will be verbal pitches with discussion.

## Recommendations for your lightning talk

Think about your talk as a short pitch.  It will be helpful to practice your talk beforehand!  Keep it short, succinct and to the point.

Bolded and capitalized for as much effect as possible:

**HAVE YOUR DATA IN HAND AS SOON AS POSSIBLE**

There is no penalty for having to switch topics or datasets in the middle of the project, provided that you can still deliver on the other portions of this work. However, if you can get the data in hand as soon as possible, you can prevent yourself a lot of extra work.

## Deliverables

Be prepared to discuss 3 potential topics with your peers.

## Useful Resources

- [How to Find the Data You Need](http://flowingdata.com/2009/10/01/30-resources-to-find-the-data-you-need/)
- [16 Ways to Prepare for a Lightning Talk](https://www.semrush.com/blog/16-ways-to-prepare-for-a-lightning-talk/)
## [Google Datasets Search Tool](https://toolbox.google.com/datasetsearch)

# Capstone Proposel

### Team members:
- **Basmah Alabdulatif**
- **Bader Abanmi**

### Problem Statment

Nowadays, the movie industry is one of the largest entertainment industries. It has been estimated that there are 500000 movies produced up to this point. Lately, Saudi Arabia is moving toward investing on entertainment. Therefore, giving the possibility that soon there will be a Saudi Production Film. In order to move on the right path of creating a blockbuster movie we will analyze what features contribute to a movie being successful. Beside popularity and revenue, the Oscar is the main measure of a movie’s success. Therefore, it is the highest honor in film making. We will collect IMDB  data to create a dataset that will help us achieve our goal.

### Data: 

**We collected our data using three sources:**
- Scrapping IMDB website.
- IMDB API
- IMDBPY library

Using the previous tools, we created a dataset of more than 10,000 movies produced between 2000 and 2017. For each year we took the top 250 movies in terms of popularity, then we collected randomly 4% of the remaining movies to assure diversity in all respects.

### Evaluation method:

We will consider the latest Oscar event to be the main evaluation matric by comparing our model’s prediction with actual results.

### Time frame:

This project is due before 19 December 2019

### Potential challenges:

- Since we dont know what features contribute to the prediction of the Oscar winners, we are trying to maximize the number of features and examine each. 
-	Retrieving data from three different sources is time consuming.
-	There is no clear documentation for the libraries we are using.
-	We are not sure that the Oscar is the prime predictor, therefore, we may consider other measures.
-	Most of the features are categorical which needs to be taken into consideration.


