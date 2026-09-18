# Stock Market Prediction and Chatbots
This project is based on AI Models and predicts the stock market and charts with other persons

# There are two models 
* Chatbots
* Stock Market Predictor

# Chatbots has the following things
### 1. Installing Necessary Libraries
- pip install nltk

### 2. Importing Required Libraries
import nltk <br>
import re <br>
from nltk.chat.util import Chat, reflections

### 3. Downloading NLTK Datasets
nltk.download('punkt') <br>
nltk.download('averaged_perceptron_tagger')

# Stock Market Predictor has the following things

### Importing Libraries

import numpy as np <br>
import pandas as pd <br>
import matplotlib.pyplot as plt <br>
import seaborn as sb <br>

from sklearn.model_selection import train_test_split <br>
from sklearn.preprocessing import StandardScaler <br>
from sklearn.linear_model import LogisticRegression <br>
from sklearn.svm import SVC <br>
from xgboost import XGBClassifier <br>
from sklearn import metrics <br>

import warnings <br>
warnings.filterwarnings('ignore')

