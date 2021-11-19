# Big_Data_Project
Projet de Big-Data relatif aux signaux d'achat et de vente de cryptomonnaies issus d'analyse de données en provenance de Twitter
#ON IMPORTE PLEIN DE PACKAGES
import os
import tweepy as tw
import pandas as pd
import datetime

import matplotlib.pyplot as plt
import seaborn as sns
import itertools
import collections

import nltk
from nltk.corpus import stopwords
import re
import networkx

from textblob import TextBlob
from textblob_fr import PatternTagger, PatternAnalyzer

import six

import warnings
warnings.filterwarnings("ignore")

sns.set(font_scale=1.5)
sns.set_style("whitegrid")
