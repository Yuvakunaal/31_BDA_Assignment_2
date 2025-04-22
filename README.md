# Spark Model Implementations

This repository contains implementations of three different machine learning models using Apache Spark.

## Files Overview

1.  **Classification Model (one.ipynb)**

    * Implements a classification model using Spark's ML library.
    * Dataset: Iris dataset.
    * Model: Logistic Regression.
    * Key steps:
        * Spark session initialization.
        * Data loading and preprocessing (using VectorAssembler).
        * Train/test split.
        * Model training.
        * Prediction.
        * Accuracy evaluation.

2.  **Clustering Model (two.ipynb)**

    * Implements a clustering model using Spark's ML library.
    * Dataset: Iris dataset (without target column).
    * Model: KMeans.
    * Key steps:
        * Spark session initialization.
        * Data loading and feature assembling.
        * Model training.
        * Cluster prediction.
        * Evaluation using Silhouette Score.
        * Display of cluster centers.

3.  **Recommendation Engine (three.ipynb)**

    * Implements a recommendation engine using Spark's ML library.
    * Dataset: Movie ratings dataset (ml-20m).
    * Model: Alternating Least Squares (ALS).
    * Key steps:
        * Spark session initialization.
        * Data loading and preprocessing.
        * Train/test split.
        * Model training.
        * Prediction.
        * Evaluation using Root-Mean-Square Error (RMSE).
        * Generation of user and movie recommendations.
    
