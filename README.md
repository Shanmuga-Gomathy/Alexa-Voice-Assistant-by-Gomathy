# Alexa-Voice-Assistant-by-Gomathy
 
# 🗣️ Python Voice Assistant (Alexa-like)

A Python-based offline/online voice assistant that uses speech recognition and text-to-speech to interact with users. It can play songs, tell jokes, fetch weather updates, read Wikipedia summaries, and more — all via voice commands.

---

## 🔍 Features

- 🎶 Play Songs – Searches YouTube and plays your requested music.
- 🌦️ Weather Info – Fetches live weather using WeatherAPI.
- 📚 Wikipedia Summaries – Gives concise info about topics or people.
- 🤣 Jokes – Uses JokeAPI to make you laugh.
- 💬 Motivational Quotes – Encouraging messages to lift your mood.
- 🎙️ Voice Wake & Stop – Commands like “Hey Alexa” or “Stop” are supported.

---

## 🧠 Technologies Used

- speech_recognition – Speech-to-text from microphone
- pyttsx3 – Offline text-to-speech
- wikipedia – Fetches 2-line summaries
- pywhatkit – Plays YouTube videos
- webbrowser – Opens YouTube songs
- requests – Fetches jokes & weather data

---

## 📦 File Structure

.
├── voice_assistant.py     # Main program
├── requirements.txt       # Python dependencies
└── README.md              # You're reading it

---

## 🚀 Setup Instructions

1. Clone the repository or download the files.

2. Install dependencies:
   pip install -r requirements.txt

3. Get a WeatherAPI key:  
   - Sign up at https://www.weatherapi.com  
   - Replace the placeholder `api_key` in the script with your own.

4. Run the assistant:
   python voice_assistant.py

---

## 🔐 Required APIs

- WeatherAPI – Required for weather info (Free tier available)
- JokeAPI – No key required

---

## 🎤 Sample Voice Commands

- “Play Shape of You”
- “Tell me about Einstein”
- “What’s the weather in Delhi?”
- “Tell me a joke about cats”
- “Motivate me”
- “Stop”
- “Hey Alexa” (to wake the assistant again)

---

## 🤖 Notes

- The assistant uses Google Speech Recognition (requires internet).
- Text-to-speech works offline.
- Jokes and weather fetching require internet.

---

## 📄 License

This project is free and open-source under the MIT License.
