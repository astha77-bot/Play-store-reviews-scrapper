# Play-store-reviews-scrapper

Step1:Code as per your required criteria that your're expecting from reviews csv file.
Ste2:Scrap reviews from Google play store applications using app package.    
![alt text](https://github.com/[astha77-bot]/[Play-store-reviews-scrapper]/blob/[main]/app_package.jpg?raw=true)
Step3:Use Pandas to convert and save the dataset into CSV files from json.    

# Setup

#### Let’s install the required packages and setup the imports:
```
%watermark -v -p pandas,matplotlib,seaborn,google_play_scraper
CPython 3.6.9
IPython 5.5.0
pandas 1.0.3
matplotlib 3.2.1
seaborn 0.10.0
```
```
google_play_scraper 0.0.2.3
import json
import pandas as pd
from tqdm import tqdm
import seaborn as sns
import matplotlib.pyplot as plt
from pygments import highlight
from pygments.lexers import JsonLexer
from pygments.formatters import TerminalFormatter
from google_play_scraper import Sort, reviews, app
%matplotlib inline
%config InlineBackend.figure_format='retina'
sns.set(style='whitegrid', palette='muted', font_scale=1.2)
```


# References
Google Play Scraper for Python
