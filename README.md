# 30DaysOfCode
Continuous improvement is key! Not sure where I first read about this, but I just found this post by [lifehack.org](https://www.lifehack.org/788823/continuous-improvement) that highlighted the philosophy of Kaizen, the practice of continuous improvement. This resonated with me a lot, so I decided to set a goal to code every day of October! 

After going through the almost the entire month I realized I really liked the visual aspect of this, so I decided to keep this going indefinitely! Tracking progress allows me to see my growth and motivates me to keep going :)

## Overview
**Topics Explored:** Scraping, Multiprocessing, Gradient Boosted Trees (GBT), Visualization, Content Creation, Dimensionality Reduction, Data Cleaning, Data Visualization, Data Exploration, Object Oriented Programming (OOP), Data Wrangling, Databases, Statistics, Automation

**Tools I used so far:** 
* (Python) _concurrent.futures, bs4, requests, multiprocessing, threading, numpy, matplotlib, plotly, seaborn, sqlite3, ebooklib, collections, sklearn, pandas;_ (SQL); (C++); (git); (Medium)

## Daily Breakdown
* **Oct 1: (requests, bs4, re, concurrent.futures, nltk, and pandas)** [Scraped readlightnovel.me to create a light-novels dataset](https://github.com/yuvalofek/scraping-light-novel-data)
* **Oct 2: (concurrent.futures, Threading, Multiprocessing)** [A comparison of multi- and single core multiprocessing for matrix multiplication in Python](https://github.com/yuvalofek/MultiprocessingMatMul)
* **Oct 3: (xgboost)** [Implemented xgboost from scratch! (xgboost part 1)](https://github.com/yuvalofek/py_xgboost)
* **Oct 4: (xgboost, boosting)** [Implemented boosting and added to previously created xgboost trees (xgboost part 2)](https://github.com/yuvalofek/py_xgboost)
* **Oct 5: (xgboost, boosting, plotly)** [Finished xgboost project! Added multi-dim input feature and aproximate splitting (xgboost part 3)](https://github.com/yuvalofek/py_xgboost)
* **Oct 6: (git, PyTest, Circle.Ci)** Set up [git](https://git-scm.com/) on my PC! (I ran into problems with this before, so I opted to use desktop app/web interface locally and git for remote server work). I also studied unit testing using using PyTest and Circle.ci. 
* **Oct 7: (SQL, sqlite)** [Tested out sqlite3 for running SQLite](https://github.com/yuvalofek/sqlite_test)
* **Oct 8: (Seaborn)** [Added visualization in seaborn to my multiprocessing project](https://github.com/yuvalofek/MultiprocessingMatMul)
* **Oct 9: (PCA, DevOps, Blogging)** Watched a couple of videos on PCA (which I found similar to SVD, a procedure I love), started going through a DevOps course on YouTube, and began writing a Medium post on SPPPACY (I have been meaning to do this last one for a long time and finally got to it!) 
* **Oct 10: (SQL, sqlite, ebooklib, bs4, re, collections)** [I made a dataset for ingredient pairings](https://github.com/yuvalofek/Ingredient-Recommendation) 
* **Oct 11: (SQL, streamlit, flask)** Took some time to dig in deeper on SQL and web developement using Python so I can make the ingredient pairings project into an app 
* **Oct 12: (PCA, NumPy, Sklearn)** [Coded up PCA in Numpy and compared results with sklearn](https://github.com/yuvalofek/PCA)
* **Oct 13: (Spark, PyPark)** watched and read tutorials on PySpark and Spark
* **Oct 14: (medium)** went back and edited the medium post i wrote on Oct 9... hopefully I get it out soon
* **Oct 15: (C++)** [I coded Othello in C++ from scratch!](https://github.com/yuvalofek/othello)
* **Oct 16: (hugo, portfolio)** Watched some tutorials on making a portfolio website
* **Oct 17: (hugo, portfolio)** Put some more work into the porfolio
* **Oct 18: (A/B testing)** Read about A/B testing
* **Oct 19: (Statistics)** Started 365 Data Science statistics course
* **Oct 20: (Data cleaning)** [Went and cleaned the data I generated from the light novels cite](https://github.com/yuvalofek/scraping-light-novel-data)
* **Oct 21: (Statistics, PySpark)** Continued statistics course and read more about PySpark (on tutorialpoint)
* **Oct 22: (Seaborn, Pandas)** [Basic data exploration on the scraped novel data](https://github.com/yuvalofek/scraping-light-novel-data)
* **Oct 23: (Seaborn, Pandas)** [Continued the data exploration and visualization for the light novel dataset](https://github.com/yuvalofek/scraping-light-novel-data)
* **Oct 24: (PySpark)** Figured out how to run PySpark on Google Colab
* **Oct 25: (Rasterio, concurrent.futures)** [Created a tool to match tif files between 2 directories](https://github.com/yuvalofek/tif_matcher)
* **Oct 26: (Rasterio, concurrent.futures)** [More work on the tif matching tool](https://github.com/yuvalofek/tif_matcher)
* **Oct 27: (Rasterio, concurrent.futures)** [Finished the tif matching tool](https://github.com/yuvalofek/tif_matcher)

## Topics I am interested in looking into: 
### High priority
- [X] git \[Oct 6\]
- [ ] Parallelization
  - [X] Multithreading \[Oct 2\]
  - [ ] Cloud (AWS/GCP/Azure)
  - [ ] PySpark
- [ ] Bread and Butter
  - [X] PCA \[Oct 9\]
  - [X] A/B Testing \[Oct 18\]
  - [ ] SQL
    - [X] SQLite \[Oct 7\]
    - [ ] Project 
  - [ ] Feature engineering
  - [X] Data cleaning \[Oct 20\]
  - [X] Data wrangling \[Oct 10\]
- [ ] Quality of Life
  - [ ] Pytest
  - [ ] Documentation - Read the Docs
  - [ ] Docker
- [ ] Web
  - [ ] Streamlit
  - [ ] Flask ?
  - [ ] Fast API ?
- [ ] Data Vizualization
  - [ ] Tableau
  - [X] Seaborn \[Oct 8\]
- [ ] Statistics
  - [ ] Theory
  - [ ] scipy.stats (more in depth) 
  - [ ] statsmodels 
- [ ] ML
  - [X] xgboost \[Oct 5\]
  - [ ] AutoML
    - [ ] Auto-sklearn
    - [ ] TPOT
  - [ ] sklearn (more in depth)
- [X] Scraping \[Oct 10\]
  - [X] requests \[Oct 1\]
  - [X] bs4 (HTML) \[Oct 1\]
  - [X] ebooklib - Epubs \[Oct 10\]


### Lower Priority
- [ ] unbalanced-learn (sampling)
- [ ] Specific ML tools
  - [ ] lightgbm
  - [ ] Graph ML
- [ ] Time Series
  - [ ] prophet
  - [ ] greykite
  - [ ] sktime
- [ ] More General Purpose Tools
  - [ ] Kubernetes
  - [ ] Dask 
- [ ] Understanding the low level 
  - [X] C++ - Review \[Oct 15\]
  - [ ] CUDA
  - [ ] GPU Programming
  - [ ] Numba
  - [ ] Cython
- [ ] More Viz tools
  - [ ] Plotly
- [ ] More DB
  - [ ] MongoDB
  - [ ] Snowflake
