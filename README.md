# Recommender-System
Zhichao Yang, Tian Pan, Yiying Huang

Personalization Theory final project

After writing a simple collaborative filtering algorithms from scratch earlier in the course, we sought to implement a recommendation system at scale. The data we use is the Amazon electronics product data spanning May 1996-July 2014. We used PySpark to analyze the data and implemented three machine learning algorithms.

Rating Data download link: http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/ratings_Electronics.csv

This project was written in PySpark. The repository contains following files in the Code folder:

'AMZ ALS.ipynb': Alternating least square model and related evaluation.

'AMZ BASELINE.ipynb': Baseline model and related evaluation.

'AMZ LSH.ipynb': Locality sensitive hashing model and related evaluation.

'AMZ FPM.ipynb': Frequent pattern mining and related evaluation.

'E4571 Final Report.pdf': Project report with code explanation (need to download for correct format).

'saved data'folder: Saved table for using in FPM
