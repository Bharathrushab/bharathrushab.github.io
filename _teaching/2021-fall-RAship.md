---
title: "Graduate Research Assistant (UPenn)"
collection: teaching
type: "Graduate Research"
permalink: /teaching/2021-fall-RAship
venue: "World Well-Being Project, University of Pennsylvania"
date: 2021-09-01
location: "Philadelphia, U.S.A."
---

Research Assistant to Dr. [Lyle Ungar](https://www.cis.upenn.edu/~ungar/), Professor in Computer and Information Science at Penn Engineering and Psychology at the School of Arts & Sciences, and, Dr. [Sharath Chandra Guntuku](https://sharathg.cis.upenn.edu), an Assistant Professor (Research) in the Department of Computer and Information Science at the University of Pennsylvania.

Research Overview
======

Professor [Lyle Ungar](https://www.cis.upenn.edu/~ungar/) is a renowned expert in the field of Artificial Intelligence and his research group actively develops explainable machine learning, deep learning, and natural language processing methods for psychology and medical research. We are currently working on leveraging Natural Language Processing and Multi-Task Learning to predict depression symptoms from Reddit posts, and analyze the language use of users with different depression symptoms.


My Contribution
======
Mine the data from over 50 different subreddits that possibly resonate with the 4 broader groups (Diet, Physical Activities, Substance Use & Smoking) using the pushshift API
Shortlist the subreddits based on number of posts, comments and members of subreddits
Perform exploratory data analysis on the finalized 22 subreddits containing approximately 1 Million posts and 2.7 Million comments
Leverage DLATK package for Python to identify latent topics present in the posts and comments through Latent Dirichlet Allocation (LDA; Blei et al., 2003)
Perform temporal analysis on the topics generated to record inference

Differential Language Analysis ToolKit (DLATK)
======

[Citation](https://aclanthology.org/D17-2010/)

DLATK is an end to end human text analysis package, specifically suited for social media and social scientific applications. It is written in Python 3 and developed by the [World Well-Being Project (WWBP)](https://wwbp.org/) at the University of Pennsylvania and Stony Brook University. It contains:

1. feature extraction
2. part-of-speech tagging
3. correlation
4. prediction and classification
5. mediation
6. dimensionality reduction and clustering
7. wordcloud visualization

DLATK can utilize:

1. Mallet for creating LDA topics
2. Stanford Parser
3. CMU’s TweetNLP
4. pandas dataframe output

