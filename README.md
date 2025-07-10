# 💰 Crypto Currency chatbot


This is a simple AI-powered chatbot built using **Chainlit**, **Binance API**, and **Gemini (OpenAI-compatible)** to fetch real-time cryptocurrency prices like `BTCUSDT`, `ETHUSDT`, and more.

---

## 🚀 Features

- Ask for any coin’s real-time USD price (e.g., `BTCUSDT`, `ETHUSDT`, `SOLUSDT`)
- Chat-style interface powered by Chainlit
- Gemini AI model used to understand and respond
- Uses Binance API for accurate and live prices

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/crypto-agent.git
cd crypto-agent
````


#2. Create virtual environment

python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate


#3. Install dependencies




# 🔐 Setup .env File
Create a .env file in the root directory and add your Gemini API Key:

GEMINI_API_KEY=your_gemini_api_key_here
🔑 You can get a free Gemini API key from:
https://aistudio.google.com/app/apikey

# 🧠 Run the Chatbot
chainlit run main.py
It will open a browser window where you can chat with your Crypto Assistant.

# 💬 Example Prompts
What is the price of BTCUSDT?

Give me the ETHUSDT price.

Fetch price of SOLUSDT
