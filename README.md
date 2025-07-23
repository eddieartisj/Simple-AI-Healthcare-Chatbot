# 🩺 Simple AI Healthcare Chatbot

A basic AI-powered chatbot built with Python to assist users with general healthcare inquiries. This project demonstrates how rule-based logic and NLP techniques can simulate a healthcare assistant capable of answering questions about symptoms, conditions, and general wellness advice.

---

## 📌 Features

- Responds to general healthcare-related questions
- Uses simple natural language processing to understand user input
- Includes fallback responses for unknown queries
- Interactive console-based user experience

---

## 🧠 How It Works

This chatbot uses basic string matching and keyword analysis to determine the intent behind a user's input. The logic is structured with conditional statements and loops to provide a response that is contextually relevant.

Key components:
- `greetings`: Responds to greetings like "hi" or "hello"
- `symptoms_keywords`: Detects common symptom-related terms like "fever", "cough", or "headache"
- `emergency_keywords`: Triggers emergency responses when words like "emergency", "urgent", or "help" are mentioned
- `fallback_response`: Provides a general fallback when input is not recognized

---

## ⚙️ How to Run

1. Clone this repository or download the `.ipynb` file.
2. Open the notebook in [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/).
3. Run all cells sequentially.
4. Start chatting in the final cell where user input is prompted.

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Basic NLP (string matching, keyword detection)

---

## 🚨 Disclaimer

This chatbot **does not provide real medical advice**. It is a simulated assistant meant solely for educational purposes. For any health concerns, always consult a licensed healthcare provider.

---

## 📈 Future Improvements

- Add integration with medical APIs (e.g., Healthline, Mayo Clinic)
- Implement a proper NLP model using spaCy or Hugging Face Transformers
- Include user authentication and conversation logging
- Deploy as a web or mobile app



