This README file is for CA04: Ensemble Models

Data Source and Contents:

The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. The following is a description of our dataset:

•	Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]

•	Number of attributes (Columns): 7

•	Number of instances (Rows): 48,842

To Import:

import numpy as np

import pandas as pd

import matplotlib as plt

import matplotlib.pyplot as pltpy

from sklearn.preprocessing import LabelEncoder

from sklearn.tree import DecisionTreeClassifier

from sklearn.ensemble import RandomForestClassifier

from sklearn.ensemble import AdaBoostClassifier

from sklearn.ensemble import GradientBoostingClassifier

from xgboost import XGBClassifier

from sklearn.metrics import accuracy_score, roc_auc_score

Notes for reviewer:

Every section in the CA04 - Ensemble Models.ipynb is labeled the same as the instructions PDF. I have also added some sub-headings to help show what I am doing in various steps. 

The answers to the written questions are in the PDF file in the CA04 folder and I also put them in my code for your convenience. 

Make sure you run everything in the order that it is shown. 

There are comments in the code to help explain what the code is doing at every step!

If you have any questions or something is not running properly on your end, please reach out to me on MS Teams! Happy Grading! :)

Here is a link to it on google colab: https://colab.research.google.com/drive/1bN86_lUurEa7FbD1HFa3ccmqFZfkdhRu?usp=sharing
