# 🎬 Movie Review Sentiment & Toxicity Analysis (NLP)

An intelligent NLP-based system that analyzes movie reviews by detecting **sentiment, emotions, and toxicity** using multiple NLP techniques and models.

---

## 🚀 Features

- 🔍 Sentiment Analysis (Positive / Negative / Neutral)
- 📊 Polarity Scoring using TextBlob
- ⚡ VADER Compound Score Analysis
- ☣️ Toxicity Detection using Detoxify (AI model)
- 😊 Basic Emotion Detection (Joy, Anger, Neutral)
- 💬 Real-time text input analysis (CLI-based)

---

## 🧠 Tech Stack

- **Python**
- **NLTK**
- **TextBlob**
- **VADER Sentiment**
- **Detoxify (Deep Learning Model)**

---

## 📌 How It Works

1. User enters a movie review
2. System processes text using:
   - TextBlob → polarity
   - VADER → sentiment score
   - Detoxify → toxicity detection
3. Outputs:
   - Sentiment (Positive / Negative / Neutral)
   - Emotion (Joy / Anger / Mixed)
   - Toxicity Score

---

## 📸 Sample Output


Enter text: This movie was amazing but some scenes were horrible

Sentiment: Positive
Polarity: 0.65
VADER Compound: 0.78
Emotion: Joy
Toxicity Score: 0.02


---

## ⚙️ Installation

```bash
pip install nltk textblob vaderSentiment detoxify

Download required NLTK data:

import nltk
nltk.download('punkt')
nltk.download('vader_lexicon')
▶️ Run the Project
python main.py
📊 Use Cases
🎥 Movie review analysis
🛡️ Content moderation systems
💬 Social media sentiment tracking
📈 Customer feedback analysis
📈 Future Improvements
🌐 Web app using Streamlit
📊 Dashboard visualization
🤖 Advanced emotion detection using deep learning
🧾 Dataset-based evaluation with accuracy metrics
👨‍💻 Author

Muhammad Anas
🔗 GitHub: https://github.com/anas7272

🔗 LinkedIn: https://linkedin.com/in/muhammadanas
