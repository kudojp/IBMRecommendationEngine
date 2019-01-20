# Disaster Response Pipeline Project

## Project overview

This is my 5th project of Udacity Data Scientist Nanodegree.

In this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles for them.



## Project tasks
This project is divided into the following 5 tasks

I. Exploratory Data Analysis

* Before making recommendations of any kind, I explored the data I worked with for the project.  

II. Rank Based Recommendations

To get started in building recommendations, I first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, I assumed that articles with the most interactions were the most popular.

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, I looked at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users.

IV. Content Based Recommendations

Using your NLP skills, I developed a content based recommendation system. You are encouraged to complete a content based recommendation system

V. Matrix Factorization

Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using your decomposition, I  got an idea of how well you can predict new articles an individual might interact with. It wasn't great in this case.



## Repo Structure

.
├── README.md
├── Recommendations_with_IBM.html
├── Recommendations_with_IBM.ipynb
├── data
│   ├── articles_community.csv
│   └── user-item-interactions.csv
├── project_tests.py
├── top_10.p
├── top_20.p
├── top_5.p
└── user_item_matrix.p
