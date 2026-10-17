# Multilingual Text-to-Speech

A simple multilingual Text-to-Speech web application built with Python, Streamlit, and Google Text-to-Speech (gTTS).

## Features

- Convert written text into speech.
- Support for English, Hindi, Kannada, Marathi, Tamil, and Telugu.
- Option to generate slower speech.
- Listen to generated audio directly in the application.
- Download generated speech as an MP3 file.
- Simple and interactive Streamlit interface.

## Technologies Used

- Python
- Streamlit
- Google Text-to-Speech (gTTS)
- BytesIO for in-memory audio processing

## Supported Languages

| Language | Code |
|---|---|
| English | en |
| Hindi | hi |
| Kannada | kn |
| Marathi | mr |
| Tamil | ta |
| Telugu | te |

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/multilingual-text-to-speech.git
cd multilingual-text-to-speech
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

If your Python file is named `app.py`, run:

```bash
streamlit run app.py
```

## How to Use

1. Enter the text you want to convert.
2. Select a language.
3. Enable the slow-speech option if needed.
4. Click **Convert to Speech**.
5. Listen to the generated audio.
6. Click **Download MP3** to save the audio.

## Project Structure

```text
multilingual-text-to-speech/
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Requirements

An internet connection is required because gTTS uses Google's online Text-to-Speech service.

## Author

Add your name and GitHub profile here.

## Disclaimer

This project is intended for educational purposes. Audio generation depends on internet connectivity and the availability of the gTTS service.
.
