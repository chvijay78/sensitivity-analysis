# Sentiment Analysis with Sarcasm Detection (Jupyter Notebook)
This project performs sentiment analysis (Positive / Negative / Neutral) on user input text, while detecting sarcasm using zero-shot classification. It uses two Hugging Face models:
RashidNLP/Amazon-Deberta-Base-Sentiment for sentiment analysis
facebook/bart-large-mnli for sarcasm detection via zero-shot learning
✅ All logic is written in a Jupyter Notebook, no web server required.

🚀 Features
💬 Accepts any text as input
⚡ Predicts sentiment using a fine-tuned DeBERTa model
🤨 Detects sarcasm using a zero-shot classifier
🔁 Adjusts sentiment if sarcasm is detected
✅ Works entirely within a notebook environment


▶️ How to Use

Open the notebook:
jupyter notebook Sentiment_Analysis.ipynb

Run the cells step-by-step:
Load the model
Enter your text input (e.g., "Oh great, another Monday. Just what I needed.")
Get the predicted sentiment

📄 License
This project is for educational use.
Models used are under their respective licenses via Hugging Face.
