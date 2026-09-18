# Stock Market Prediction and Chatbots
This project is based on AI Models and predicts the stock market and charts with other persons

# There are two models 
* Chatbots
* Stock Market Predictor

# Chatbots has the following things
### 1. Installing Necessary Libraries
- pip install nltk

### 2. Importing Required Libraries
import nltk "<br>"
import re "<br>"
from nltk.chat.util import Chat, reflections

### 3. Downloading NLTK Datasets
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')

# Stock Market Predictor has the following things

### Importing Libraries

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sb

from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression
from sklearn.svm import SVC
from xgboost import XGBClassifier
from sklearn import metrics

import warnings
warnings.filterwarnings('ignore')

