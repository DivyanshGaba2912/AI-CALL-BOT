# Voice-Enabled Dental Clinic Assistant

A Python-based voice assistant designed for a dental clinic to handle patient interactions such as booking appointments, answering service-related queries, and providing emergency contact information.

The assistant integrates speech recognition, text-to-speech, generative AI, and MongoDB for persistent appointment storage.

---

## Features

* Voice-based interaction using microphone input
* Speech-to-text using Google Speech Recognition
* Text-to-speech responses using gTTS and pygame
* AI-powered conversational fallback using Google Gemini
* Appointment booking with availability checks
* MongoDB integration for storing appointments
* Handles common clinic queries (services, hours, emergency contact)

---

## Tech Stack

* **Language:** Python 3
* **Speech Recognition:** speech_recognition
* **Text-to-Speech:** gTTS, pygame
* **AI Model:** Google Gemini (Generative AI)
* **Database:** MongoDB Atlas

---

## Prerequisites

* Python 3.8 or higher
* Working microphone
* Active internet connection
* MongoDB Atlas account
* Google Generative AI API key

---

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/your-username/dental-voice-assistant.git
   cd dental-voice-assistant
   ```

2. Install dependencies:

   ```
   pip install speechrecognition gtts pygame pymongo google-generativeai
   ```

3. Set the API key as an environment variable:

   Linux / macOS

   ```
   export GOOGLE_API_KEY=your_api_key_here
   ```

   Windows PowerShell

   ```
   setx GOOGLE_API_KEY your_api_key_here
   ```

---

## Usage

Run the application:

```
python bot.py
```

The assistant will start listening for voice input and guide the user through available options.

---

## Project Structure

```
bot.py
README.md
LICENSE
.gitignore
```

---

## Security Notes

* Do not commit API keys or database credentials
* Always use environment variables for sensitive information

---

## License

This project is licensed under the MIT License.
