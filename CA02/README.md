This README file is for CA02: Naive Bayes - Spam Email Detection

Assignment Description:
In this exercise we shall train the model with set of emails labelled as either from Spam or Not Spam. There are 702 emails equally divided into spam and non spam category. Next, we shall test the model on 260 emails. We shall ask model to predict the category of this emails and compare the accuracy with correct classification that we already know.

Data:
- Find under CA02 Folder in zipped files
- train-mails (442 files)
- test-mails (260 files)

To Import:
import os
import numpy as np
from collections import Counter
from sklearn.naive_bayes import GaussianNB
from sklearn.metrics import accuracy_score
from google.colab import drive
drive.mount('/content/drive')

Notes for reviewer:
- Assumes you have the data saved in the same folder path as layed out in the instructions pdf '/content/drive/My Drive
/MSBA_Colab_2020/ML_Algorithms/CA02/Data'
- Under each block on code is a text cell with line by line explanations of what is happening in the code above
- Some of the code explanations are included in comments inside the code

Here is a link to it on google colab: https://colab.research.google.com/drive/1b3mqRQqP8gqu7hLTejXVH9J6an4wYCbV?usp=sharing
