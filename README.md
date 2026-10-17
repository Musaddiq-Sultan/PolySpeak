# PolySpeak

A simple command-line Text-to-Speech (TTS) converter built with Python and `gTTS` (Google Text-to-Speech). It allows users to convert input text into synthesized speech audio files in over 50 languages and dialects.

## Features

* **Multi-language Support:** Converts text to audio across a wide variety of languages (English, Spanish, French, Hindi, Urdu, German, Mandarin, and many more).
* **Flexible Input:** Accepts full language names (e.g., "Spanish", "English") or standard ISO language codes (e.g., "es", "en").
* **Auto-Numbered Audio Exports:** Automatically increments and saves output files with standardized filenames (`01 Name.mp3`, `02 Name.mp3`, etc.).
* **Continuous Processing:** Infinite loop design allows generating multiple audio files sequentially without re-launching the application.

## Prerequisites

Ensure you have Python installed along with the required dependencies:

* **Python:** `3.x`
* **gTTS Library:** Install via pip:

  ```bash
  pip install gtts
  ```

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/musaddiq-sultan/PolySpeak.git
   cd PolySpeak
   ```

2. Install the dependency:

   ```bash
   pip install gtts
   ```

## How to Use

Run the script directly from your terminal:

```bash
python main.py
```

### Steps to Convert Text to Speech

1. **Enter Text:** Type or paste the text you want to convert to speech when prompted (`Text:`).
2. **Enter Language:** Specify the target language by name or code (e.g., `English`, `en`, `Urdu`, `ur`, `Spanish`, `es`).
3. **Enter File Name:** Provide a label for the output file (e.g., `greeting`).
4. **Output Generation:** The audio file will be saved in the working directory in the format `01 filename.mp3`. The script will then prompt you for the next conversion.