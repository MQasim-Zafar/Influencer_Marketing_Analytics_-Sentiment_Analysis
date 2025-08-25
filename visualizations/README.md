# 📊 Influencer Sentiment Analysis – Visualizations

This section presents key evaluation metrics and visual insights from the sentiment analysis models (VADER, BERT, RoBERTa) used in this research.

---

## 🌀Histogram: Model Evaluation Metrics across Scores

These Histogram charts compares models sentiment classification both with emojis and without, indicating thier individual performance in accurately labeling sentiment as positive or negative, as compared to the Survey results that are used as ground-truth sentiment labels. These histograms further allow an easy analysis of the models skewness errors e.g VADER tends to gravitate towards neutural labels rather than polarized labels
![Brand Distribution](Plots/plot_1.png)
![Brand Distribution](Plots/plot_2.png)

---

## Model Errors

MAE, MAD, MSE, RMSE for all models with and without emojis in a Radial chart.
Tighter fit indicates lower error so RoBERTa outperforms other models both with and without Emojis.

![Error Bar Plot](Plots/plot_3.png)
![Error Bar Plot](Plots/plot_6.png)

Accuracy, Precision, Recall and F1 Scores from actual survey responses for each model.

![APRF Bar Plot](Plots/plot_13.png)

## 📦 BoxPlot: Comparing model rankings of inlfuencers with survey rankings using test set
This boxplot allows for an easy visual comparison of influencers ranked by each models mean sentiment results, as well as the distribution across models.

![BoxPlot](Plots/plot_31.png)


## 📦 Final Influencer Rankings by Mean Scores across Models using dataset

Influencer Rankings by Mean Sent Scores vary by the models used for sentiment analysis. Since RoBERTa has the least error and the best performance, its rankings can be considered most accurate.

![Influencer Ranking](Plots/plot_34.png)
![Influencer Ranking](Plots/plot_35.png)
![Influencer Ranking](Plots/plot_36.png)
---

## 💡 Summary

These visualizations demonstrate the comparative strengths and weaknesses of traditional vs transformer-based sentiment models, especially in handling emoji-enhanced input.

