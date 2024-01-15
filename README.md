# Machine Learning Models Repository

This repository contains Jupyter notebooks implementing machine learning models for a text classification task. The task involves distinguishing between essays written by students and those generated by large language models (LLMs). Various machine learning models have been explored, including Logistic Regression, Random Forest, Support Vector Machine (SVM), and BERT (Bidirectional Encoder Representations from Transformers).

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Models](#models)
   - [Logistic Regression](#logistic-regression)
   - [Random Forest](#random-forest)
   - [Support Vector Machine (SVM)](#support-vector-machine-svm)
   - [BERT Model](#bert-model)
4. [Usage](#usage)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

This repository hosts notebooks for different machine learning models developed to tackle a text classification problem. The task involves identifying whether an essay was written by a student or generated by an LLM. The models explore various approaches, from traditional methods like Logistic Regression, Random Forest, and SVM, to advanced techniques using BERT.

## Dataset

The dataset comprises approximately 10,000 essays, including examples from students and essays generated by various large language models. The essays are responses to one of seven essay prompts. The training set includes essays from two prompts, while the remaining essays compose the hidden test set.

## Models

### Logistic Regression

The Logistic Regression model serves as a baseline for text classification, leveraging simplicity and interpretability.

### Random Forest

The Random Forest model is an ensemble learning approach that aims to capture complex relationships within the data for improved classification.

### Support Vector Machine (SVM)

The Support Vector Machine (SVM) model employs a linear kernel to find an optimal hyperplane for effective separation of student-written and LLM-generated essays.

### BERT Model

The BERT model utilizes pre-trained contextual embeddings to understand and classify essays based on their writing styles.

## Usage

To run the notebooks, make sure you have the required dependencies installed. Each notebook is self-contained and includes sections for data loading, preprocessing, model training, and evaluation.

```bash
pip install -r requirements.txt
jupyter notebook
```

## Results

Detailed results for each model, including accuracy and additional metrics, are available in the respective notebooks. Please refer to the individual model notebooks for comprehensive evaluation summaries.

