# Alexa-Voice-Assistant-by-Gomathy
🗣️ Python Voice Assistant (Alexa-like) with Weather, Jokes, Wikipedia & YouTube
A Python-based voice assistant using speech_recognition, pyttsx3, and various APIs that responds to natural voice commands. You can ask it to play music, fetch weather, tell jokes, provide info, and more!

🔍 Features
🎶 Play Songs – Searches YouTube and plays requested music.

🤣 Tell Jokes – Pulls safe jokes from JokeAPI (random or topic-specific).

🌦️ Weather Info – Uses WeatherAPI to fetch real-time weather by city.

📚 Wikipedia Summary – Summarizes any topic in 2 lines.

💬 Motivational Quotes – Built-in list of inspiring messages.

🎙️ Wake/Stop Commands – Use voice to start, stop, or pause assistant.

📦 Technologies Used
speech_recognition – Converts voice to text

pyttsx3 – Text-to-speech (offline)

requests – HTTP API calls

wikipedia – Fetches summaries

pywhatkit – For YouTube interaction (optional)

webbrowser – Opens browser to play songs

📁 File Structure
css
Copy
Edit
.
├── voice_assistant.py     # Main code file
├── README.md
├── requirements.txt
└── .gitignore
🚀 Setup Instructions
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Replace API Key
In get_weather(city), replace api_key = 'your_api_key_here' with your own from https://www.weatherapi.com/.

Run the assistant:

bash
Copy
Edit
python voice_assistant.py
🔐 Required APIs
✅ WeatherAPI Key

✅ JokeAPI (No key required)

🧠 Voice Commands You Can Try
"Play [song name]"

"Tell me about [topic]"

"Tell me a joke" / "Make me laugh about dogs"

"Weather in [city]"

"Motivate me"

"Thank you" / "Stop" / "Exit"

"Hey Alexa" (wake word)
