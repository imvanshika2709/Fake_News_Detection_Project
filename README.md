# Fake_News_Detection_Project

This project is focused on building a machine learning model to detect fake news. By analyzing labeled datasets, the model is trained to classify news articles as either "Fake" or "True."

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Fake news is a significant challenge in today's digital world. This project aims to address this issue by developing a machine learning model that can accurately identify fake news articles. The project involves data preprocessing, model training, and evaluation using a variety of metrics.

## Installation

To run this project, ensure that you have Python installed. You'll need to install the following libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

##Usage

1. Clone the repository

```bash
git clone https://github.com/imvanshika2709/fake-news-detection.git
```
2. Navigate to the project directory:

```bash
cd fake-news-detection
```

3. Run the Jupyter notebook:

```bash
jupyter notebook Fake_News_Detection.ipynb
```

## Datasets
The project uses two datasets labeled as "Fake" and "True." These datasets are loaded and processed to balance the classes before being used for training the machine learning model.

## Model

The model is built using the following steps:

1. Data Loading: The datasets are loaded and merged into a single DataFrame
2. Data Preprocessing: The data is cleaned, and necessary transformations are applied.
3. Model Training: A machine learning model is trained to classify the news articles. Four techniques to determine the results of the model, namely **Logistic Regression**, **Decision Tree Classifier**, **Gradient Boost Classifier**, **Random Forest Classifier**.
4. Evaluation: The model is evaluated using accuracy, classification reports, and other metrics.

## Results

We evaluated each classifier's performance using metrics such as accuracy, precision, recall, and F1 score. The results are documented in the project files.





