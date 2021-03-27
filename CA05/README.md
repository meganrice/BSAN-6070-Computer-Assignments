## This README file is for CA05: Logistic Regression

### Data Source and Contents:

Cardiovascular Disease (CVD) kills more people than cancer globally. A dataset of real heart patients collected from a 15 year heart study cohort is made available for this assignment. The dataset has 16 patient features. Note that none of the features include any Blood Test information.

Data Column (Feature Name) Descriptions:
cvd_4types: Label Column. 0 indicates “No Risk”, 1 indicates “Risk Present” age_s1: Age in Years race: 1 - White, 2 - Black, 3 – Other ....
Get the definition of rest of the 16 features by searching on the feature name at the following web page: https://sleepdata.org/datasets/shhs/variables

### To Import:

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sn

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LogisticRegression

from sklearn.metrics import confusion_matrix, roc_auc_score, roc_curve

### Notes for reviewer:

Every section in the CA05 - Logistic Regression is titled appropriately under the table of contents section in colab.

The conclusion to the assignment is in the PDF file in the CA05 folder and I also included a section for it in my code for your convenience.

Make sure you run everything in the order that it is shown.

There are comments in the code to help explain what the code is doing at every step!

If you have any questions or something is not running properly on your end, please reach out to me on MS Teams! Happy Grading! :)

Here is a link to it on google colab: https://colab.research.google.com/drive/1qdtNcY-ZW3m94xqCAgwO0tmQ6zFA0xXa?usp=sharing
