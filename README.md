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

### Configuration   
1. Setting Up Your API Key
2. Obtain an API key from OpenAI.
3. Create a .env file in the root directory of the project.
4. Add your API key to the .env file as follows:
   1. plaintext
   2. Copy code
   3. OPENAI_API_KEY='your_openai_api_key_here'
   4. Make sure to replace 'your_openai_api_key_here' with your actual API key.

### Usage
To start the JARVIS AI Assistant, run the script from your terminal:
1. bash
2. Copy code
3. python jarvis_ai_assistant.py
4. The application will initialize and wait for your voice commands. Speak to the microphone to interact with JARVIS.

### Example Commands
1. "What is the weather today?"
2. "How are you?"
3. "Tell me a joke."
4. Say "quit", "exit", or "bye" to stop the assistant.

### Development

Feel free to fork this project and customize it to your liking. You can add more features, improve the AI's responses, or integrate more services.

### Troubleshooting

1. Microphone Issues: Ensure your microphone is set as the default recording device and is functioning properly.
2. API Key Problems: If you receive errors related to the OpenAI API key, double-check your .env file for correctness.
