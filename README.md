# Jarvis

A Python voice assistant that listens to spoken commands and responds using OpenAI's GPT models. Named after the obvious inspiration. Supports a range of tasks from answering questions to fetching information and automating simple things.

## Features

- Voice input using speech recognition
- Text-to-speech responses so it talks back to you
- Powered by OpenAI GPT for intelligent answers
- Can fetch information, answer questions, and run simple commands
- Hands-free interaction

## Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/MohammadAbbas393/Jarvis
cd Jarvis

# 2. Install dependencies
pip install -r requirements.txt

# 3. Add your OpenAI API key
# Create a .env file or set it directly in the script
OPENAI_API_KEY=your_key_here

# 4. Run the assistant
python jarvis.py
```

Speak into your microphone when prompted. Jarvis will listen, process your command, and respond out loud.

## Requirements

- Python 3.8+
- openai
- speechrecognition
- pyttsx3 or gTTS
- pyaudio (for microphone input)

Install with:

```bash
pip install openai speechrecognition pyttsx3 pyaudio
```

## Notes

- A working microphone is required
- You need an OpenAI API key (available at platform.openai.com)
- On some systems, pyaudio requires additional system packages to install

