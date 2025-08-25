# Influencer Marketing Sentiment Analysis with Emojis 🧠📊✨

While social media metrics often focus on followers, likes, shares, and subscribers, **user comments** are an often overlooked data source that can provide valuable insights into audience sentiment toward influencers - crucial when recruiting influencers for marketing campaigns. Ideally, higher levels of positive sentiment would reflect better audience perception of products promoted by the influencer, and vice versa.

Moreover, in sentiment analysis, **emojis** have become increasingly important as a medium for users to convey nuanced emotions and attitudes.

This project explores how Natural Language Processing (NLP) models handle **emojis** in the context of **sentiment analysis** on **influencer social media pages**, particularly Twitter. The project conducts a **comparative evaluation of sentiment classification performance** — both with and without emojis — using VADER, DistilBERT, and RoBERTa.

[![View Analysis and Visualizations](https://img.shields.io/badge/View-Data%20Visualizations-blue?style=for-the-badge&logo=plotly)](https://github.com/MQasim-Zafar/Research-Project-Influencer-Sentiment-Analysis/blob/main/Findings%20and%20Visualisations/README.md)


## 📌 Objectives

- Investigate how emojis affect sentiment analysis outcomes.
- Compare sentiment classification models on text with and without emojis.
- Determine which model most accurately reflects human sentiment perception.
- Use sentiment analysis results to **rank influencers** for potential use in influencer marketing campaigns.

---

## 🔍 Research Overview

### 🧾 Data Collection
- **Source**: Mined user comments from Twitter influencer pages.
- **Preprocessing**: Comments were preprocessed into two datasets — one **including emojis** and one **excluding emojis**.

### 🛠️ Models Used
1. **VADER** – Rule-based, lexicon-based model
2. **DistilBERT** – Transformer-based, distilled version of BERT
3. **RoBERTa** – A robustly optimized BERT variant

All models were used **without fine-tuning**, reflecting their **default performance** out-of-the-box.

### 🧪 Ground Truth Evaluation
- A **survey-based test set** was manually created by sampling real user comments.
- Human annotators labeled:
  - **Sentiment Category**: Positive, Neutral, Negative
  - **Sentiment Intensity**: High, Medium, Low

### 📈 Evaluation Metrics

#### Sentiment Label Classification:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

#### Sentiment Score Prediction:
- **Mean Absolute Deviation (MAD)**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

---

## 🧠 Key Findings

- **RoBERTa outperformed all other models** on both datasets (with and without emojis).
- **VADER ranked second**, offering solid baseline performance.
- **DistilBERT was the least accurate**, especially in capturing sentiment intensity.
- **Emojis improved sentiment classification accuracy** for all models.
- **Inclusion of emojis led to better alignment with human sentiment perception**.

---

## 🧲 Influencer Ranking

Using RoBERTa (the best-performing model), influencers were **ranked by descending Mean Sentiment**. The influencer with the **highest positive sentiment** was recommended as the most suitable for **influencer marketing campaigns**.

---

## 📁 Repository Structure

Research-Project-Influencer-Sentiment-Analysis/
│
├── data/ # Contains raw and preprocessed datasets
├── models/ # Scripts for using VADER, DistilBERT, RoBERTa
├── evaluation/ # Metric calculation and performance comparison
├── visualizations/ # Plots and graphs of results
├── ground_truth/ # Survey data and labeling methodology
├── influencer_ranking/ # Scripts for ranking influencers based on sentiment
└── README.md # Project overview and instructions

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/MQasim-Zafar/Research-Project-Influencer-Sentiment-Analysis.git
Install required packages (e.g., Transformers, Scikit-learn, NLTK):

pip install -r requirements.txt
Run analysis notebooks or scripts from the root folder:

jupyter notebook
⚙️ Run on Google Colab
Click the links below to run the notebooks directly in Google Colab:

📓 Model Comparison Notebook

📓 Influencer Sentiment Ranking Notebook

📌 Note: Make sure to connect your Google Drive to access the datasets if required.

📬 Contact
For questions or collaboration inquiries, please open an issue or contact via GitHub.
