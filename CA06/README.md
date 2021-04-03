## This README file is for CA06: kNN based Recommender Engine

### Data Source and Contents:

The data contains thirty movies, including data for each movie across seven genres and their IMDB ratings. The labels column values are all zeroes because we aren’t using this data set for classification or regression. You can ignore this column. The implementation assumes that all columns contain numerical data.

Additionally, there are relationships among the movies that will not be accounted for (e.g. actors, directors, and themes) when using the KNN algorithm simply because the data that captures those relationships are missing from the data set. Consequently, when we run the KNN algorithm on our data, similarity will be based solely on the included genres and the IMDB ratings of the movies.

Note: 0 = No, 1 = Yes

### To Import:

import numpy as np

import pandas as pd

from sklearn.neighbors import KNeighborsClassifier, NearestNeighbors

### Notes for Reviewer:

Make sure you run everything in the order that it is shown.

Each cell's comments should clearly explain the steps associated.

If you have any questions or something is not running properly on your end, please reach out to me on MS Teams! Happy Grading! :)

Here is a link to it on google colab: https://colab.research.google.com/drive/18tOkiVx6HkVY8CkjUUTAbsLyysDDz9GX?usp=sharing
