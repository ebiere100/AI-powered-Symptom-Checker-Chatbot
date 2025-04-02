

# 🤖 AI-Powered Symptom Checker Chatbot

A simple AI-powered chatbot that helps users check possible medical conditions based on described symptoms. This project uses Natural Language Processing (NLP) and a basic knowledge base to simulate a helpful and conversational symptom checker.

---

## 🚀 Features

- 🔍 Understands free-text symptom descriptions
- 🧠 Uses AI (Hugging Face transformers) for sentiment analysis
- 🗂 Matches symptoms to common conditions using a knowledge base
- 💬 Conversational chatbot interface in the terminal
- ❤️ Shows empathy based on user input sentiment

---

## 🛠 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-symptom-checker.git
cd ai-symptom-checker

2. Install dependencies

pip install -r requirements.txt

If you don’t have a requirements.txt, install manually:

pip install transformers torch nltk scikit-learn

▶️ Usage

Run the chatbot:

python symptom_checker.py

Example:

🤖 Hi! I'm your AI Symptom Checker. Describe your symptoms (or type 'exit' to quit):
You: I feel really tired and have a cough and fever.
🤖 You may have the flu or COVID-19.

📚 How It Works

    Symptom Matching: Uses TF-IDF and cosine similarity to match user inputs to a symptom-condition knowledge base.

    Sentiment Analysis: Uses Hugging Face’s transformers to detect negative sentiment and provide empathetic responses.

    Rule-Based Engine: Simple logic to return appropriate responses based on matched conditions.

📦 File Structure

├── symptom_checker.py       # Main chatbot script
├── requirements.txt         # List of Python dependencies
└── README.md                # Project overview

✅ Future Improvements

    Add a larger, medical-grade symptom database

    Integrate with real medical APIs (e.g., Infermedica)

    Deploy as a web app using Streamlit or Flask

    Add voice input/output capability

👩‍⚕️ Disclaimer

This chatbot is not a substitute for professional medical advice. Always consult a licensed healthcare provider for serious symptoms or concerns.
📌 Credits

    Hugging Face Transformers

    NLTK

    Scikit-learn


---

Let me know if you'd like this project turned into a GitHub repository template or converted into a Streamlit app for the web!

