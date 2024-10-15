# Lyrics Extractor and Image Generator

## Project Description

The **Lyrics Extractor and Image Generator** web application transforms audio files into visual art. Users can upload MP3 files, transcribe audio to text, summarize content, and generate images based on the summary using advanced AI models.

---

## Features

- **MP3 to Text Transcription**: Upload MP3 files; transcribed to text using Google's speech recognition.
- **Text Summarization**: Summarizes transcribed text into a concise description using OpenAI's GPT-3.5-turbo.
- **AI-Powered Image Generation**: Generates images from summarized text using OpenAI's DALL-E.
- **User-Friendly Interface**: Intuitive HTML interface for easy uploads and result viewing.
- **Dynamic Feedback**: Displays transcribed text, summary, and generated image in an organized format.

---

## Technical Specifications

- **Backend**: FastAPI for handling uploads, transcription, summarization, and image generation.
- **Frontend**: HTML and jQuery for dynamic updates.
- **Libraries**: Uses `speech_recognition` and `pydub` for audio processing, and OpenAI’s API for summarization and image generation.
- **Environment**: Configured with `python-dotenv` for API keys.

---

## How It Works

1. **Upload**: Users upload an MP3 file.
2. **Conversion**: MP3 converted to WAV format.
3. **Transcription**: Audio is transcribed to text.
4. **Summarization**: Text is summarized.
5. **Image Generation**: Image generated based on the summary.
6. **Display**: Shows transcription, summary, and image.

---

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js (if needed)
- OpenAI API access

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lyrics-extractor-image-generator.git
   cd lyrics-extractor-image-generator
