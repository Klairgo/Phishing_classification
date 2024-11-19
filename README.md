# Phishing Classification
Phishing websites pose a big threat to anyone using the internet and the main goal of a phishing website is to steal user information such as a login email and/or password. It is one of the most common cyber attacks and since the average cost of a data breach for an organization is $4 million we can see why this is seen as a big problem. With the internet’s anonymous nature, it can be very difficult or even impossible to distinguish between a legitimate website and a fake website.  In this project, we will examine two main implementations, namely a decision tree and a feed-forward neural network to help detect whether a website is used for phishing purposes. The goal is to see if one implementation outperforms the other. We will be exploring multiple exploratory data analysis techniques to preprocess and understand the data before we feed it into the two machine learning algorithms.

## Dataset:

[Phishing Websites](https://archive.ics.uci.edu/dataset/327/phishing+websites)

## How to run (locally):
```bash
git clone https://github.com/Klairgo/Phishing_classification.git
```

### Make sure to have "uv" installed:

- Visit [uv](https://docs.astral.sh/uv/) for more information.

### Install the required packages:
```bash
uv sync
```

### Run the notebooks:

- Use the [Jupyter vs-code extension](https://github.com/Microsoft/vscode-jupyter) to run the code blocks
- Select the uv virtual environment (.venv) as the jupyter kernel.
- Run the preprocess.ipynb first to create and download the necessary data files. 
- When the data folder and files are created, you can run the DT.ipynb and NN.ipynb.

### Note:
- PyTorch: "Completely reproducible results are not guaranteed across PyTorch releases, individual commits, or different platforms. Furthermore, results may not be reproducible between CPU and GPU executions, even when using identical seeds."
- This can mean that the exact results that was captured during this project could differ when running on another environment. That said, the observed differences should still be clear when running the notebooks.

## Files:
    |-- README.md:       Readme file
    |-- pyproject.toml:  Project description used by uv (including dependencies)
    |-- uv.lock:         Used for dependecies 
    |-- tree_gini.pdf:   Tree created by decision tree in plotted in a pdf
    |-- src
        |-- preprocess.ipynb: Notebook to download and preprocess the data.
        |-- DT.ipynb:         Notebook implementing decision tree.
        |-- NN.ipynb:         Notebook implementing neural network.
    |-- .gitignore:      File git has to ignore.
    |-- .python-version: Specifies python version

