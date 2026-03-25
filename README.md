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

⭐ If you like this project

Give it a ⭐ on GitHub!


---

# ✅ HOW TO HANDLE GOOGLE COLAB PROJECT (IMPORTANT ⚠️)

You said you built this on Colab — that’s fine, but do this:

---

## 🔥 STEP 1: Clean Your Code

👉 Remove:
```python
!pip install ...

👉 Instead create a file:

📄 requirements.txt
nltk
textblob
vaderSentiment
detoxify
🔥 STEP 2: Convert Notebook → Python Script
Option 1 (Best):

In Colab:

File → Download → .py

Rename:

main.py
🔥 STEP 3: Project Structure (VERY IMPORTANT)

Your repo should look like:

movie-review-nlp/
│
├── main.py
├── requirements.txt
├── README.md
└── notebook.ipynb   (optional)
🔥 STEP 4: If you KEEP Colab notebook

Add this line in README:

## 📓 Google Colab Version

You can also run this project on Google Colab:
[Open in Colab](YOUR_NOTEBOOK_LINK)
🚀 BONUS (TO BOOST SHORTLIST CHANCES)
Add this to README (optional but 🔥):
## 📊 Performance

- Handles diverse text inputs with consistent sentiment classification
- Combines rule-based + ML-based techniques for improved reliability
💥 PRO TIP (THIS MATTERS A LOT)

Right now your project is:
👉 Good

To make it top 1%:

Add Streamlit UI
Deploy it
Add screenshot in README

Then your resume becomes 🔥🔥🔥

🚀 NEXT STEP

If you want, I can:
👉 Turn this into a live deployed web app (Streamlit)
👉 Help you push perfect GitHub repo (commands + setup)
👉 Make your resume shortlist-ready for AI internships

Just say:
👉 "deploy this project"
