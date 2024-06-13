# JARVIS AI Assistant

## Overview
The JARVIS AI Assistant is a Python application that uses speech recognition and text-to-speech technologies to interact with users through spoken commands. Powered by OpenAI's GPT models, the assistant can perform a variety of tasks and respond intelligently to user input.

## Features
- **Voice Recognition**: Converts spoken language into text using Google's speech recognition API.
- **Text-to-Speech**: Reads out responses using the gTTS (Google Text-to-Speech) API.
- **Conversational AI**: Leverages OpenAI's powerful models to generate human-like responses.

## Prerequisites
Before you can run the JARVIS AI Assistant, you need to install several packages and set up environment variables. You will also need a valid API key from OpenAI.

### Dependencies
- Python 3.6+
- `pygame` for handling audio playback.
- `gtts` for Google Text-to-Speech functionality.
- `speech_recognition` for converting spoken words into text.
- `python-dotenv` for loading environment variables from a `.env` file.
- `openai` for interfacing with OpenAI's GPT models.

### Installation
To install the required packages, run the following command in your terminal:

```bash
pip install pygame gtts speech_recognition python-dotenv openai
```
