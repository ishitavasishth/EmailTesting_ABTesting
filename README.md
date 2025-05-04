# ✉️ Email Subject Line Performance Predictor

Predict whether an email subject line will get opened—using NLP, classification modeling, and good old marketing instincts. 

---

## 🚀 Project Overview

Marketers obsess over email subject lines—but how do you know what actually works?

This project simulates 500 email campaigns and uses natural language features like **urgency**, **personalization**, and **length** to predict open rate likelihood. It also suggests **better-performing copy** to improve subject line performance.

---

## 🔍 Features

- 📊 Simulated campaign dataset (500 rows, 100% generated)
- ✂️ Feature engineering: urgency, personalization, sentiment, emoji, word count
- 🧠 Classification model (Random Forest)
- 🧪 A/B-style open rate testing with urgency vs no urgency
- 💬 Interactive predictor: test your own subject lines in Colab
- 💡 Word suggestion engine: recommends urgency & personalization phrases

---

## 📌 Example Predictions

| Subject Line                                       | Predicted Open Probability |
|----------------------------------------------------|----------------------------|
| `urgent: update your payment info today`          | 0.93                       |
| `🎉 just for you – claim your reward`             | 0.60                       |
| `for you: exclusive early access inside`          | 0.65                       |
| `today only – last chance to save 30%`            | 0.29                       |
| `what's happening?`                                | 0.00                       |

---

## 🧪 How It Works

1. Simulated subject lines include urgency & personalization elements.
2. Each line is scored with:
   - `Has_Urgency`: boolean
   - `Has_Personalization`: boolean
   - `Subject_Length`, `Word_Count`
3. A Random Forest model predicts the chance of opening.
4. A recommendation engine suggests stronger words when missing.

---

## 💡 Sample Word Suggestions

If your subject lacks urgency:
> Try adding urgency: `final hours`

If your subject lacks personalization:
> Try adding personalization: `just for`

---

## 💻 How to Run

1. Open the Colab notebook  
2. Run all cells to simulate data and train the model  
3. Use the interactive `test_subject_line()` function to try your own copy

---

## 📈 Future Ideas

- Batch testing from uploaded CSVs
- Streamlit UI for live demos
- Sentiment & emotion classification
- Copywriting leaderboard (best-performing phrases)

---

---

## 📌 Tech Stack

- Python (Google Colab)
- Pandas, scikit-learn, TextBlob
- Seaborn + Matplotlib for EDA
- [Optional] Streamlit for UI

---

## 📣 Let’s Connect

Built by a marketing analytics student who believes in making numbers talk.  
Have ideas or feedback? Drop a line on [LinkedIn](https://www.linkedin.com/in/ishitavasishth/) or check out the [GitHub](https://github.com/ishitavasishth) repo.
