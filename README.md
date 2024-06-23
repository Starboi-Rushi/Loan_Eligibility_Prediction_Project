# Import all necessary libraries and modules
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

from sklearn.ensemble import RandomForestClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score, roc_auc_score
from sklearn.metrics import classification_report, confusion_mal_score
from sklearn.model_selection import GridSearchCV
from sklearn.preprocessing import StandardScaler, LabelEncoderatrix
from sklearn.model_selection import train_test_split, cross_v
from sklearn.svm import SVC

from imblearn.over_sampling import RandomOverSampler

import warnings
warnings.filterwarnings('ignore')
warnings.simplefilter('ignore')
