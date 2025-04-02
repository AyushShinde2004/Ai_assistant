🎙️ Grace - Your AI Voice Assistant 🤖✨
Python
License

Grace is a voice-controlled AI assistant built with Python that can:
🎵 Play music on Spotify/YouTube
⏰ Set reminders
🌤️ Check weather
🔊 Control system volume
🗣️ Have natural conversations (Gemini AI)
...and much more!

🚀 Features
Feature	Command Example
Music Playback 🎶	"Play Bohemian Rhapsody on Spotify", "Pause YouTube"
Reminders ⏰	"Remind me in 20 minutes to take a break"
System Control 🖥️	"Set volume to 50%", "Open YouTube Music"
Conversational AI 💬	"Tell me about quantum computing", "Search for Python tutorials"
Smart Switching 🔄	Auto-switches voice API keys when limits are reached
⚙️ Setup
📋 Requirements
Python 3.8+

ffmpeg (for audio processing)

API Keys (see .env.example)

🔧 Installation
bash
Copy
# Clone repo
git clone https://github.com/yourusername/grace-ai-assistant.git
cd grace-ai-assistant

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys
🔑 Required APIs
ElevenLabs (Voice)

Google Gemini

Spotify Developer

OpenWeatherMap

Porcupine (Wake Word)

🎛️ Usage
bash
Copy
python grace.py
Wake Word: "Hey Grace" 👂
Try commands like:

"What's the weather?" ☀️

"Play my liked songs on shuffle" 🔀

"Set volume to 70%" 🔊

"Remind me in 1 hour to call mom" ⏰

🛠️ Technical Stack
Voice Recognition: speech_recognition, pvporcupine

Text-to-Speech: ElevenLabs API 🗣️

AI Chat: Google Gemini 🤖

Music Control: spotipy, Selenium 🎵

System Integration: pycaw, winsound 💻

📜 License
MIT License - Feel free to customize and extend!

💡 Pro Tip: Add your frequent commands to the sites list for quick access!

🌟 Star this repo if you find it useful! → GitHub Stars
