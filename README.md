# 🧠 GPT-based Smart Assistant

This is a voice-controlled AI assistant built using Python, OpenAI's GPT model, and speech libraries. It listens to your voice, sends your command to OpenAI's GPT-4o model, and speaks out the intelligent response.

## ✨ Features

- 🎤 Voice command input (Speech-to-Text)
- 🤖 Smart replies using OpenAI's GPT-4o
- 🔊 Text-to-Speech responses
- 🌐 Voice-activated browser commands (e.g., "Open YouTube")
- 👋 Gracefully ends the session when you say "bye"

## 📁 Project Structure

GPT-Smart-Assistant/
├── apikey.py # File storing your OpenAI API key
├── assistant.py # Main Python code (rename your script to this for clarity)

makefile
Copy
Edit

### 📌 Note
Make sure to create a file named `apikey.py` and define your API key like this:

```python
# apikey.py
api_data = "your_openai_api_key_here"
🚀 Getting Started
1. Clone the repository
git clone https://github.com/your-username/GPT-Smart-Assistant.git
cd GPT-Smart-Assistant
2. Install Dependencies
pip install openai SpeechRecognition pyttsx3 pyaudio
⚠️ If pyaudio installation fails, install it manually based on your OS. Example for Windows:

pip install pipwin
pipwin install pyaudio
3. Run the Assistant
python assistant.py
Replace assistant.py with your actual script name if different.

🔒 Disclaimer
This project uses OpenAI API and may incur charges if your free quota is used up.

Voice recognition may vary depending on your microphone quality and background noise.

🙌 Acknowledgments
This project was built by following a tutorial from NxtWave and customized further.
