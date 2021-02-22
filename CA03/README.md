This README file is for CA03: Decision Tree Algorithm

Data Source and Contents:

The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. The following is a description of our dataset:
•	Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]
•	Number of attributes (Columns): 7
•	Number of instances (Rows): 48,842

Data:

Find in CA03 Folder in zipped file.

To Import:

import os

import numpy as np

import pandas as pd

import matplotlib as plt

import matplotlib.pyplot as pltpy

from sklearn.tree import DecisionTreeClassifier

from sklearn.preprocessing import LabelEncoder

from sklearn.externals.six import StringIO  

from IPython.display import Image  

from sklearn.tree import export_graphviz

import pydotplus

from sklearn.metrics import accuracy_score, classification_report, confusion_matrix, roc_auc_score, plot_roc_curve, roc_curve, RocCurveDisplay, recall_score, precision_score, f1_score

import seaborn as sns

Notes for reviewer:

Every section in the CA03 - Decision Tree Algorithm.ipynb is labeled exactly the same as the instructions PDF (Part1 - Part 10). The answers to the questions are in the PDF file in the CA03 folder and I also put them in my code for your convenience. Make sure you run everything in the order that it is shown. There are comments in the code to help explain what the code is doing. 

If you have any questions or something is not running properly on your end, please reach out to me on MS Teams! Happy Grading! :)

Here is a link to it on google colab: https://colab.research.google.com/drive/1bN86_lUurEa7FbD1HFa3ccmqFZfkdhRu?usp=sharing
