# Emotion Classification on GoEmotions with TensorFlow

This repository showcases multi-label emotion classification with BERT, RoBERTa, and ELECTRA models using TensorFlow on TPU, demonstrated in a Jupyter Notebook.

## Dataset: GoEmotions

The GoEmotions dataset is a human-annotated, multi-label dataset extracted from Reddit comments. It is designed to capture a wide range of emotions, making it ideal for emotion classification tasks. The dataset contains:

- 27 distinct emotions (we use a subset of these in our analysis).
- Neutral category.
- Annotations from multiple raters.

## Table of Contents
1. [Project Setup](#project-setup)
2. [Data Acquisition](#data-acquisition)
3. [Data Preprocessing](#data-preprocessing)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Baseline Model: SVM](#baseline-model-svm)
6. [Deep Learning Models](#deep-learning-models)
7. [Evaluation](#evaluation)

## Project Setup
- TPU Preparation
- Required Libraries

## Data Acquisition
- Loading the Dataset

## Data Preprocessing
- Preparing the Dataset
- Text Preprocessing
- Train, Val, and Test sets
- Handling Class Imbalance

## Exploratory Data Analysis
- Label Distribution Visualization
- Comment Lengths Histograms
- Word Clouds
- Box Plot

## Baseline Model: SVM
- Tokenization and TF-IDF
- Model Training
- Evaluation

## Deep Learning Models
- Configurations
- BERT
- RoBERTa
- ELECTRA

## Evaluation
- Final Model Selection
- Receiver Operating Characteristic

## Requirements
- TensorFlow 2.x
- TensorFlow Text
- TensorFlow Hub
- TensorFlow Addons
- TensorFlow Model Garden
- scikit-multilearn
- emoji
- wordcloud
- scikit
- pandas
- numpy
- matplotlib

## Usage
1. Clone the repository.
2. Install the required packages.
3. Open the Jupyter Notebook and run the cells.

## Author

Amin Najafgholizadeh
