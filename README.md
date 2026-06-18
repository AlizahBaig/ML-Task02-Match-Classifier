# ⚽ Football Match Outcome Classifier (Task 2)

## 📌 Project Overview
This project uses machine learning to classify and predict the outcomes of international football matches. 

By looking at decades of historical FIFA World Cup performance data, the model calculates the exact winning probabilities for Team A or Team B, or whether the match is likely to result in a draw.

---

## 🚀 Live App Link
You can test and play with the live football predictor directly in your web browser here:

👉 **[Click Here to Open the Live Web Interface](https://huggingface.co/spaces/alizahbaig/MLtask02)**

---

## 📊 How It Works
The app uses a **Logistic Regression** classification model trained on historical international football results from Kaggle. You give it 2 simple inputs:

* **Home Team / Team A:** Select the first country from the dropdown list.
* **Away Team / Team B:** Select the second country from the dropdown list.

The app instantly displays the exact win/loss/draw percentages and crowns a predicted statistical winner.

---

## ⚙️ How to Run It Locally

If you want to run this code on your computer or inside Google Colab, follow these steps:

1. **Install the required libraries:**
   ```bash
   pip install gradio kagglehub pandas scikit-learn numpy
