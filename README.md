# 🤖 AI Voice Assistant

## 🚀 Overview
This AI-powered voice assistant integrates multiple services, including speech recognition, text-to-speech, web automation, and Spotify playback. It can:
- Recognize voice commands 🎙️
- Play YouTube videos 📺
- Control system volume 🔊
- Set reminders ⏰
- Provide weather updates ☁️
- Control Spotify playback 🎵

## 🛠️ Technologies Used
- **Speech Recognition** (`speech_recognition`)
- **Text-to-Speech** (`pvleopard`, `elevenlabs API`)
- **Web Automation** (`selenium`, `undetected_chromedriver`)
- **Media Playback** (`pygame`, `pydub`)
- **Music Streaming** (`spotipy`)
- **Environment Variables** (`dotenv`)

## 🔧 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-voice-assistant.git
   cd ai-voice-assistant
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your `.env` file:
   ```plaintext
   GEMINI_API_KEY=your_api_key
   WEATHER_API_KEY=your_weather_api_key
   SPOTIFY_CLIENT_ID=your_spotify_client_id
   SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
   SPOTIFY_REDIRECT_URI=your_redirect_uri
   ```

## 🎙️ Usage
Run the assistant:
```bash
python main.py
```

### Example Commands:
- **"Play Imagine Dragons on Spotify"** 🎶
- **"Set a reminder in 10 minutes"** ⏳
- **"What's the weather like?"** 🌦️
- **"Turn volume to 50%"** 🔈

## 📝 Features
### 🗣️ Speech Recognition & AI Responses
- Uses Google Speech Recognition to process voice commands.
- Interacts with the Gemini API for AI-generated responses.

### 🎶 Music & Video Control
- Plays music on **Spotify**.
- Plays videos on **YouTube** using Selenium automation.
- Controls **system volume**.

### ⏰ Reminder System
- Set and check reminders with automatic voice alerts.

### ☁️ Weather Updates
- Retrieves real-time weather information via the **OpenWeather API**.

## 🤝 Contribution
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit changes:
   ```bash
   git commit -m "Added new feature"
   ```
4. Push and create a pull request.

## 📜 License
This project is licensed under the MIT License.

---
🚀 Built with Python and Passion! ❤️
