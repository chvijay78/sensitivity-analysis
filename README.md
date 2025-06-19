# 🤖 Sentiment Analysis with Sarcasm Detection

This project performs **sentiment analysis** (Positive / Negative / Neutral) on any user input text, with **sarcasm detection** using **zero-shot classification**. It runs entirely in a **Jupyter Notebook** — no web server or deployment required.

---

## 🚀 Features

- 💬 Accepts any free-form text as input
- ⚡ Predicts sentiment using a fine-tuned **DeBERTa** model: `RashidNLP/Amazon-Deberta-Base-Sentiment`
- 🤨 Detects sarcasm using zero-shot classification with: `facebook/bart-large-mnli`
- 🔁 Adjusts sentiment if sarcasm is detected (e.g., flips Positive to Negative)
- ✅ All logic implemented in a single Jupyter Notebook

---

## ▶️ How to Use

1. **Open the Notebook**  
   Launch the file `Sentiment_Analysis.ipynb` in Jupyter Notebook.

2. **Run Step-by-Step**  
   Execute the notebook cells one by one:
   - Load the sentiment and sarcasm models
   - Enter your custom text input  
     _Example_: `"Oh great, another Monday. Just what I needed."`
   - View the predicted sentiment and sarcasm status

3. **Output**  
   The notebook prints whether the input is sarcastic and adjusts sentiment accordingly.

---

## 🧠 Example

Input:  
`"Oh fantastic, another bug in the code!"`

Output:  
- Sarcasm Detected: ✅  
- Original Sentiment: Positive  
- Adjusted Sentiment: **Negative**

---

## 📦 Dependencies

Install the following Python packages before running:

```bash
pip install transformers torch
