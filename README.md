# Sentiment Analysis for DKI Jakarta Governor Candidates 2024

This repository contains the code, data, and models used for sentiment analysis on public opinions about the candidates for the 2024 Governor election of DKI Jakarta. The project uses a combination of Word2Vec embeddings and a BiLSTM model for sentiment classification. Additionally, sentiment labeling is performed using a pre-trained BERT model.

## Table of Contents
- [Project Overview](#project-overview)
- [Folder Structure](#folder-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Notebooks](#notebooks)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The goal of this project is to analyze public sentiment towards the candidates for the 2024 Governor election of DKI Jakarta using natural language processing (NLP) techniques. The Author employ the following steps:
1. Crawling public opinions from social media.
2. Text preprocessing (case folding, cleaning, etc.).
3. Sentiment labeling using BERT.
4. Word embedding using Word2Vec.
5. Sentiment classification using a BiLSTM model.

## Folder Structure
- `data/raw/`: Contains the raw data collected through web scraping.
- `data/processed/`: Contains the preprocessed data, ready for analysis.
- `data/labels/`: Contains data that has been assigned a sentiment label.
- `notebooks/`: Contains all the Python scripts for crawling, preprocessing, labeling with IndoBERT and classification with embedding word2vec.
- `models/`: Pre-trained models (Word2Vec).
- `results/`: Contains the output files such as classification reports and confusion matrices.

## Installation
To run the code in this repository, you need to install the necessary dependencies. The Author recommend using a Python virtual environment.

```bash
# Clone the repository
git clone https://github.com/your-username/your-project-name.git
cd your-project-name

# Install dependencies
pip install -r requirements.txt