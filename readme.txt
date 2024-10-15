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
   ```

2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Configure environment variables in a `.env` file:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

5. Run the application:
   ```bash
   uvicorn main:app --reload
   ```

### Usage

- Navigate to `http://localhost:8000` to upload MP3 files and view results.

---

## Contributing

Contributions are welcome! Submit pull requests or open issues for improvements.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
