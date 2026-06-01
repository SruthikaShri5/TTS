# Audio Sentiment Analysis Using Whisper and DistilBERT

## Project Description

Audio Sentiment Analysis is a Natural Language Processing (NLP) and Speech Processing project that determines the sentiment expressed in a spoken audio recording. The system accepts an audio file as input, converts speech into text using OpenAI's Whisper Automatic Speech Recognition (ASR) model, analyzes the extracted text using a DistilBERT-based sentiment analysis model, and generates an audio response indicating whether the sentiment is positive or negative.

The project demonstrates the integration of Speech Recognition, Natural Language Processing, Transformer Models, Sentiment Analysis, and Text-to-Speech technologies into a single end-to-end pipeline.

---

## Objectives

* Convert speech audio into text.
* Analyze the sentiment of the extracted text.
* Classify the sentiment as Positive or Negative.
* Generate a voice response containing the prediction.
* Demonstrate practical usage of modern NLP and Deep Learning models.

---

## System Architecture

```text
Audio Input
     │
     ▼
Whisper Speech-to-Text Model
     │
     ▼
Extracted Text
     │
     ▼
DistilBERT Sentiment Analysis Model
     │
     ▼
Positive / Negative Prediction
     │
     ▼
Google Text-to-Speech (gTTS)
     │
     ▼
Audio Output
```

---

## Technologies Used

### Programming Language

* Python

### Libraries and Frameworks

* OpenAI Whisper
* Transformers
* PyTorch
* gTTS
* Google Colab

### Machine Learning Models

#### Whisper

Whisper is an Automatic Speech Recognition (ASR) model developed by OpenAI. It converts spoken language into text and supports multiple languages and accents.

Functions:

* Speech Recognition
* Audio Transcription
* Multilingual Support

#### DistilBERT

DistilBERT is a lightweight version of BERT created through knowledge distillation. It provides fast and accurate Natural Language Understanding while requiring fewer computational resources.

Functions:

* Sentiment Analysis
* Text Classification
* Natural Language Understanding

#### gTTS

Google Text-to-Speech converts text into spoken audio.

Functions:

* Speech Synthesis
* Voice Output Generation

---

## Workflow

### Step 1: Audio Upload

The user uploads an audio file in WAV or MP3 format.

Example:

```text
I am very happy with the service provided.
```

---

### Step 2: Speech-to-Text Conversion

The Whisper model processes the audio and generates a text transcript.

Output:

```text
I am very happy with the service provided.
```

---

### Step 3: Sentiment Analysis

The extracted text is analyzed using DistilBERT.

Possible outputs:

* POSITIVE
* NEGATIVE

Example:

```text
Input Text:
I am very happy with the service provided.

Output:
POSITIVE
```

---

### Step 4: Result Generation

The sentiment label is converted into a user-friendly output.

Example:

```text
Positive
```

---

### Step 5: Text-to-Speech

The final result is converted into speech using gTTS.

Output Audio:

```text
Positive
```

---

## Features

* End-to-End Audio Processing Pipeline
* Speech-to-Text Conversion
* Transformer-Based Sentiment Analysis
* Audio Response Generation
* Supports WAV and MP3 Files
* Lightweight and Easy to Deploy
* Google Colab Compatible
* Real-Time Processing Potential

---

## Installation

Install the required dependencies:

```bash
pip install openai-whisper
pip install transformers
pip install torch
pip install gtts
```

For Linux environments:

```bash
sudo apt install ffmpeg
```

---

## Usage

1. Run the notebook or Python script.
2. Upload an audio file.
3. Wait for speech transcription.
4. Perform sentiment analysis.
5. View the sentiment result.
6. Listen to the generated audio output.

---

## Sample Execution

### Input Audio

```text
I love learning Artificial Intelligence.
```

### Speech Recognition Output

```text
I love learning Artificial Intelligence.
```

### Sentiment Prediction

```text
POSITIVE
```

### Generated Audio Output

```text
Positive
```

---

## Applications

### Customer Feedback Analysis

Analyze customer opinions expressed through voice recordings.

### Call Center Monitoring

Evaluate customer satisfaction from recorded calls.

### Virtual Assistants

Understand user sentiment during interactions.

### Social Media Analytics

Analyze sentiment from audio content.

### Education

Study applications of NLP, Deep Learning, and Speech Processing.

### Healthcare

Assist in behavioral and emotional analysis based on speech content.

---

## Advantages

* High speech recognition accuracy.
* Fast sentiment prediction.
* Fully automated pipeline.
* Easy integration with web and mobile applications.
* Supports multiple audio formats.
* Uses state-of-the-art transformer models.

---

## Limitations

* Accuracy depends on audio quality.
* Background noise may affect transcription.
* Binary sentiment classification only (Positive/Negative).
* Does not detect complex emotions such as anger, fear, or sarcasm.

---

## Future Enhancements

* Multi-class sentiment analysis (Positive, Negative, Neutral).
* Emotion detection from speech.
* Real-time microphone input support.
* Multilingual sentiment analysis.
* Web application deployment using Flask or FastAPI.
* Mobile application integration.
* Advanced emotion recognition using audio features.

---

## Expected Outcome

The system successfully converts speech into text, analyzes the sentiment expressed in the speech, classifies it as Positive or Negative, and generates a corresponding audio response. This demonstrates the practical application of Speech Recognition, Natural Language Processing, Transformer Models, and Text-to-Speech technologies in a unified workflow.
