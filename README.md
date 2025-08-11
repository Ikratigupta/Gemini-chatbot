#  Gemini Chatbot (Python)

A simple terminal-based chatbot built using the *Google Gemini API* in Python.  
This chatbot can answer questions, have conversations, and run entirely in your command line.

---

## 🚀 Features
- Chat with Google's Gemini AI in real-time
- Safe API key handling using .env
- Simple and beginner-friendly Python code

---

## 📂 Project Structure

Gemini-Chatbot/ │ ├── app.py          # Main chatbot script ├── .gitignore      # Ensures .env is not uploaded └── .env            # Stores your API key

---

## 🔑 Setup Instructions

### 1️⃣ Clone this repository
```bash
git clone https://github.com/yourusername/gemini-chatbot.git
cd gemini-chatbot

2️⃣ Install dependencies

pip install python-dotenv google-generativeai

3️⃣ Add your API key

Create a .env file in the project folder and add:

API_KEY=your_real_api_key_here

4️⃣ Run the chatbot

python app.py
