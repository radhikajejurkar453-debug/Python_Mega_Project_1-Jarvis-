# Python_Mega_Project_1

# 🤖 Jarvis Voice Assistant (Python)

A simple **AI-powered voice assistant** built using Python that can perform tasks like opening websites, playing music, fetching news, and responding using AI.

---

## 🚀 Features

* 🎤 Voice recognition using SpeechRecognition
* 🔊 Text-to-speech using gTTS + pygame
* 🌐 Open popular websites (Google, YouTube, Facebook, etc.)
* 🎵 Play songs from a custom music library
* 📰 Fetch latest news headlines using News API
* 🧠 AI-powered responses using Gemini / OpenAI
* 🗣️ Wake word detection ("Jarvis")

---

## 🛠️ Technologies Used

* Python
* SpeechRecognition
* gTTS (Google Text-to-Speech)
* pygame
* requests
* Google Gemini API / OpenAI API

---

## 📂 Project Structure

```
📁 Jarvis-Voice-Assistant
│── main.py               # Main assistant script
│── musicLibrary.py       # Custom music dictionary
│── README.md             # Project documentation
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/jarvis-voice-assistant.git
cd jarvis-voice-assistant
```

### 2️⃣ Install dependencies

```bash
pip install pygame gtts SpeechRecognition requests google-generativeai openai
```

### 3️⃣ Setup API Keys

* Replace in code:

```python
newsapi = "YOUR_NEWS_API_KEY"
```

* For AI:

```python
api_key="YOUR_GEMINI_OR_OPENAI_API_KEY"
```

---

## ▶️ Usage

Run the assistant:

```bash
python main.py
```

### 🧠 How it works:

1. The assistant listens for the wake word **"Jarvis"**
2. Once activated, it listens to your command
3. Executes predefined tasks or uses AI for responses

---

## 💡 Example Commands

* "Jarvis open Google"
* "Jarvis open YouTube"
* "Jarvis play believer"
* "Jarvis tell me the news"
* "Jarvis what is AI?"

---

## ⚠️ Notes

* Ensure your microphone is working properly 🎤
* Internet connection is required 🌐
* Replace API keys before running
* Run in terminal (not IDLE for better audio support)

---

## 🧩 Future Improvements

* GUI interface 🖥️
* Wake word detection without repeating "Jarvis"
* System control (open apps, shutdown, etc.)
* Personal memory system 🧠
* Multi-language support 🌍

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgements

* Google Speech Recognition
* gTTS
* OpenAI / Gemini APIs

---

⭐ If you like this project, don’t forget to star the repo!
