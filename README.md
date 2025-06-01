# Python_Talksense

Talksense is a Python-based voice-activated virtual assistant inspired by JARVIS. It can recognize voice commands, respond using AI (OpenAI API), play music, fetch news headlines, and open websites like Google, YouTube, and more. The assistant listens for the wake word "Jarvis" to activate its functionalities.

---

## 🔧 Features

- 🎙️ Voice command recognition using `speech_recognition`
- 🧠 Smart replies using OpenAI's GPT model
- 🌐 Opens websites via voice (Google, YouTube, Facebook, LinkedIn)
- 📰 Reads latest Indian news headlines using NewsAPI
- 🎵 Plays songs from a custom music library
- 🔊 Text-to-speech using Google TTS (`gTTS`) and `pygame`

---

## 📦 Requirements

Make sure you install the required libraries before running:

# API Keys
OpenAI API Key: Replace <Your Key Here> in the script with your actual OpenAI API key.

NewsAPI Key: Replace the value of the newsapi variable with your key from https://newsapi.org

Mega project Jarvis/
│
├── main.py               # Main script
├── musicLibrary.py       # Custom music dictionary
├── README.md             # Project documentation


▶️How to Run
Connect your microphone and ensure it's working.

Navigate to the project folder.

Run the script:

bash
Copy

python main.py
Say “Jarvis” to activate the assistant.

Give voice commands like:

“Open YouTube”

“Play [song_name]”

“Tell me the news”

“Who is Elon Musk?”

💡 Tips
Use a quiet environment for better voice recognition.

Internet connection is required for OpenAI and NewsAPI functionality.

You can switch back to pyttsx3 if you want offline speech output.




