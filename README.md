README
# Sentiment Analysis in NLP Models for Influencer Marketing

## Overview

This project explores sentiment analysis techniques tailored for influencer marketing content. By leveraging NLP models like BERT and RoBERTa, it investigates how emojis impact sentiment classification performance, an important factor in social media communication.

Two core Jupyter Notebooks drive this analysis:

- **`Analysis_and_Visualisations.ipynb`**  
  Conducts data exploration, preprocessing, model evaluation, and visualizations to understand sentiment dynamics in influencer-generated content.

- **`Comparison_of_effect_of_emojis_on_sentiment_analysis_(BERT_and_RoBERTa).ipynb`**  
  Focuses on the impact of emojis by comparing model performance with and without emoji data, using both BERT and RoBERTa architectures.

## Project Structure



Analysis_and_Visualisations.ipynb
Comparison_of_effect_of_emojis_on_sentiment_analysis_(BERT_and_RoBERTa)_CLEAN.ipynb
README.md


## Motivation

Influencer marketing content — rich in emojis, shorthand, and nuanced emotional expression — poses unique challenges for sentiment analysis. This project aims to:

- Evaluate whether including emojis improves model understanding of sentiment.
- Compare performance differences between BERT and RoBERTa in this context.
- Provide visual and statistical insight into influencer messaging patterns.

## Requirements

- **Python 3.8+**
- Jupyter Notebook or JupyterLab
- Core dependencies (install via `pip` or `conda`):
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn transformers


(Optional) GPU support for model inference/training acceleration.

# Getting Started

## Clone the repo:

git clone https://github.com/MQasim-Zafar/Sentiment-analysis-in-NLP-models-for-Influencer-Marketing.git
cd Sentiment-analysis-in-NLP-models-for-Influencer-Marketing


## Set up the environment:

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt


## Run the analysis notebooks:

jupyter notebook


Then open each of the notebooks, explore the content, and run the cells sequentially.

# Notebook Highlights
## Analysis_and_Visualisations.ipynb

Loads the dataset (provide instructions if a dataset is needed).

Visualizes sentiment distribution across posts.

Evaluates baseline models and displays performance metrics (accuracy, F1-score, confusion matrix).

Includes charts that illustrate sentiment trends and patterns.

## Comparison_of_effect_of_emojis_on_sentiment_analysis_(BERT_and_RoBERTa)_CLEAN.ipynb

Preprocesses text data, with and without emojis.

Runs fine-tuned BERT and RoBERTa models on both versions.

Compares classification performance through metrics and charts.

# How to Interpret Results

Observe if models trained on content including emojis perform better in capturing true sentiment.

Examine visual comparisons (e.g., bar plots, confusion matrices) between models and input variations.

Assess which architecture—BERT or RoBERTa—handles influencer-style sentiment more effectively.

# Contributing

Contributions are welcome! You can:

Add support for more models (e.g., DistilBERT, XLNet).

Incorporate more nuanced emoji sentiment lexicons.

Extend analysis to other social media platforms or languages.

Improve documentation and environment reproducibility.

# License

MIT License

# Contact

For questions or collaborations, feel free to open an issue or reach out to m.qasimzafar111@gmail.com
