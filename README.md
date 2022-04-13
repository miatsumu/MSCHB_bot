# MSCHB_bot
Calls Music — Telegram bot + userbot for streaming audio in group calls
✍🏻 Requirements
FFmpeg
Python 3.7+
🚀 Deployment
🛠 Configuration
Copy example.env to .env and fill it with your credentials.
Install Python requirements:
pip install -U -r requirements.txt
Run:
python -m callsmusic
🐬 Docker
Build:
docker build -t musicplayer .
Run:
docker run --env-file .env musicplayer
