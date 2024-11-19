# Phishing Classification
Phishing websites pose a big threat to anyone using the internet and the main goal of a phishing website is to steal user information such as a login email and/or password. It is one of the most common cyber attacks and since the average cost of a data breach for an organization is $4 million we can see why this is seen as a big problem. With the internet’s anonymous nature, it can be very difficult or even impossible to distinguish between a legitimate website and a fake website.  In this project, we will examine two main implementations, namely a decision tree and a feed-forward neural network to help detect whether a website is used for phishing purposes. The goal is to see if one implementation outperforms the other. We will be exploring multiple exploratory data analysis techniques to preprocess and understand the data before we feed it into the two machine learning algorithms.

## How to run:
```bash
    git clone https://github.com/Klairgo/Phishing_classification.git
```

### Make sure to have "uv" installed
```bash
    pip install uv
```

### Install the required packages
```bash
    uv sync
```

- Select the uv virtual environment (.venv) as the jupyter kernel.
- Run the preprocess.ipynb first to create and download the necessary data files. 


## Files:
    |-- tree_gini.pdf                     (Decision Tree output)
    |-- src
        |-- preprocess.ipynb
        |-- DT.ipynb                      (Decision Tree)
        |-- NN.ipynb                      (Neural Network)

- preprocess.ipynb - Code for all the preprocessing of the dataset.
- DT.ipynb - Code to train and export the decision tree used to classify the websites. Hyperparameter optimization code is included in this notebook
- NN.ipynb - Code to train the neural network to classify the websites. Hyperparameter optimization code is included in this notebook.

