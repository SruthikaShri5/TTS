Audio Sentiment Analysis using Whisper and DistilBERT
Overview

This project performs sentiment analysis on audio input. The system converts speech to text using Whisper, analyzes the sentiment of the extracted text using DistilBERT, and generates an audio response indicating whether the sentiment is positive or negative.

Workflow

Audio Input → Speech-to-Text (Whisper) → Sentiment Analysis (DistilBERT) → Positive/Negative Result → Text-to-Speech (gTTS) → Audio Output

Features
Speech-to-Text conversion using Whisper
Sentiment classification using DistilBERT
Positive or Negative prediction
Audio output generation using Google Text-to-Speech (gTTS)
Supports WAV and MP3 audio files
Technologies Used
Python
Whisper
Transformers
DistilBERT
gTTS
PyTorch
Google Colab
Installation
pip install openai-whisper
pip install transformers
pip install torch
pip install gtts
Usage
Upload an audio file (.wav or .mp3).
Convert speech to text using Whisper.
Analyze the extracted text using DistilBERT.
Display the sentiment result.
Generate an audio response saying "Positive" or "Negative".
Example
Input Audio

"I am very happy today."

Extracted Text

I am very happy today.

Sentiment Result

Positive

Output Audio

Positive

Applications
Customer feedback analysis
Voice-based sentiment detection
Call center analytics
Human-computer interaction
NLP and Speech Processing projects
Future Enhancements
Multi-class sentiment analysis (Positive, Negative, Neutral)
Real-time microphone input
Multilingual speech support
Emotion detection from speech
Web application deployment
