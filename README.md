# whisper-transcriber
# 🎙️ Whisper Audio Transcription Tool

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/manilka12/whisper-transcriber/blob/main/whisper_transcriber.ipynb)

A powerful tool for transcribing audio/video content using OpenAI's Whisper model via faster-whisper. Supports multiple input sources and output formats with real-time transcription preview.

## ✨ Features

- 🔉 Support for various media sources:
  - YouTube videos
  - Google Drive files
  - Direct download URLs
  - Local file uploads
- 🚀 GPU acceleration with CUDA support
- 🌍 Multi-language support (100+ languages)
- ⏱️ Word-level timestamps
- 📊 Confidence score display
- 📁 Batch processing capabilities
- 🎞️ Automatic video-to-audio conversion
- 📄 Multiple output formats (TXT, SRT)
- 📈 Progress indicators and real-time preview

## 📥 Installation

Open in Colab - https://colab.research.google.com/drive/1wFRQQXbIbmCOTEfFo4eGOZIC0y4oJTvz?usp=sharing

1. **Google Colab:**
   - Click the "Open in Colab" button above
   - Runtime > Run all (Ctrl+F9)

🚀 Usage
Model Selection:

Choose appropriate Whisper model size based on your needs

Larger models offer better accuracy but require more resources

Media Source Setup:

Select your input source (YouTube, Drive, URL, or Upload)

Provide required parameters (URL, file path, etc.)

Transcription Configuration:

Set language (auto-detection available)

Adjust advanced settings:

Beam size (1-10)

Voice Activity Detection

Output format (TXT/SRT/Both)

Confidence scores

Timestamps

Run Transcription:
View real-time transcription preview
Download results as ZIP archive
Access individual files in /transcribed_texts
   

