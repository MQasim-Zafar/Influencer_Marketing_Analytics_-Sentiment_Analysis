# 📊 Influencer Sentiment Analysis – Visualizations

This section presents key evaluation metrics and visual insights from the sentiment analysis models (VADER, BERT, RoBERTa) used in this research.

---

## 🌀 Radar Chart: Model Evaluation Metrics

This radar chart compares four error metrics — MAE, MSE, MAD, and RMSE — across all models. A more compact shape indicates better performance.

![Radar Chart](visualizations/plots/plot_0)

---

## 📏 Bar Plot: Mean Absolute Error (MAE)

Shows the average deviation from actual survey responses for each model.

![MAE Bar Plot](visualizations/plot_1.png)

---

## ⚖️ Bar Plot: Mean Squared Error (MSE)

MSE gives greater weight to larger errors. Lower values reflect higher model accuracy.

![MSE Bar Plot](visualizations/plot_2.png)

---

## 🔍 Scatter Plot: Predictions vs Actuals

Visual comparison of predicted scores vs real sentiment scores. The closer to the diagonal line, the more accurate the prediction.

![Scatter Plot](visualizations/plot_3.png)

---

## 📈 Line Plot: Sentiment Trends Over Responses

This line plot captures how sentiment predictions vary across the sequence of influencer responses.

![Line Plot](visualizations/plot_4.png)

---

## 📦 Box Plot: Model Score Distributions

Box plots reveal the spread and consistency of sentiment scores for each model.

![Box Plot](visualizations/plot_5.png)

---

## 💡 Summary

These visualizations demonstrate the comparative strengths and weaknesses of traditional vs transformer-based sentiment models, especially in handling emoji-enhanced input.

