## Project Description
Recommendation Engine to determine which articles to show to each user from user-article interaction data available on the IBM Watson Studio platform.

The main approaches that were considered were:

Rank based recommendations which recommends the most interacted-with articles to users. 
Collaborative Filtering based recommendations, which recommends articles to users based similarity of user interactions with the article.
Matrix Factorization based recommendations, uses SVD (Singular Value Decomposition) on user-item interactions to predict which articles users may want to interact with i.e., read.

## Packages
I used the following libraries in Python:
1. Pandas
2. Numpy
3. Pickle
4. Matplotlib

## Files
README.md: Read me file (being read by you now)

articles_community.csv: csv file containing descriptions of the articles on the platform.

user-item-interactions.csv: csv file containing data on user-item interactions

Recommendations_with_IBM.ipynb: Jupyter notebook containing EDA and different recommendation functions

Recommendations_with_IBM.html: HTML file of Recommendations_with_IBM.ipynb
