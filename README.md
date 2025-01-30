# Telegram AI Chatbot

This project is a Telegram chatbot powered by AI (Gemini API) that can interact with users, process text, and provide automated responses. The bot can analyze images, files, and perform web searches, making it a versatile tool for everyday use.

## Features
- User registration and authentication
- AI-powered chat responses using Gemini API
- Image and file analysis
- Web search integration
- MongoDB integration for storing user data and logs

## Installation & Setup

### Prerequisites
- Python 3.x
- MongoDB (if you're using it locally)
- Telegram Bot API token
- Gemini API credentials

### Steps to set up:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/telegram-bot-project.git
    ```
2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set up environment variables (e.g., API keys, Telegram Bot Token).
4. Run the bot:
    ```bash
    python bot.py
    ```
5. if you use colab:
   ```
   !jupyter nbconvert --execute --to notebook --allow-errors '/content/telegram_bot/telegram_bot_main.ipynb'
  ```

### Configuration
- Update your `config.py` file with the correct Telegram Bot API token and Gemini API credentials.

## Usage
1. Start a conversation with the bot on Telegram.
2. Type any command or question to get started.
3. Use the image/file upload feature for analyzing documents.
4. Try the web search feature to get information from the internet.

## Acknowledgements
- Gemini API for AI-powered responses
- Python-telegram-bot for the Telegram Bot framework
- MongoDB for storing user data
