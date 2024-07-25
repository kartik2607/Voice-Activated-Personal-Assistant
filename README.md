
# Voice-Activated Personal Assistant

## About the Project

This Voice-Activated Personal Assistant uses pyttsx3 for text-to-speech and speech_recognition for voice input. It performs tasks like opening applications, checking the weather, sending emails, retrieving news, searching the web, and providing movie information. The assistant features hotkey-based activation for efficient and responsive interaction.

## Features

- **Voice Commands**: Interact with the assistant using voice commands.
- **Application Control**: Open applications like Notepad and Command Prompt.
- **Weather Updates**: Get current weather information for your city.
- **Email Sending**: Send emails using voice commands.
- **News Updates**: Retrieve the latest news headlines.
- **Web Search**: Search on Google and play videos on YouTube.
- **Movie Information**: Get movie details including ratings, cast, and plot summaries.
- **Hotkey Activation**: Start and stop listening with customizable hotkeys.

## Requirements

- Python 3.x
- pyttsx3
- SpeechRecognition
- keyboard
- wolframalpha
- imdbpy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kartik2607/Voice-Activated-Personal-Assistant.git
   cd voice-assistant
   ```

2. Install the required packages:
   ```bash
   pip install pyttsx3 SpeechRecognition keyboard wolframalpha imdbpy
   ```

1. Set up WolframAlpha API key:
   - Get your API key from [WolframAlpha](https://developer.wolframalpha.com/).
   - Replace the placeholder in the script with your API key.

## Usage

1. Run the assistant:
   ```bash
   python main.py
   ```

2. Use the following hotkeys to control the assistant:
   - \`Ctrl + Alt + K\` to start listening.
   - \`Ctrl + Alt + P\` to stop listening.

## Voice Commands

- **General Queries**:
  - "How are you?"
  - "What is the weather in [city]?"
  - "Give me the news."
  - "Search [query] on Google."
  - "Play [video] on YouTube."

- **Application Control**:
  - "Open Command Prompt."
  - "Open Notepad."

- **Utilities**:
  - "Send an email."
  - "Tell me about [movie]."
  - "Calculate [expression]."
