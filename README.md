# YouTube Video MCQ Generator

This project generates multiple-choice questions (MCQs) from the transcribed text of a YouTube video. The workflow involves downloading the audio from a YouTube video, transcribing the audio using the Whisper model, generating questions using a pre-trained NLP model, and creating MCQs.

## Features

- Download audio from YouTube videos.
- Transcribe the audio to text using Whisper.
- Generate questions from the transcribed text using the T5 model.
- Create multiple-choice questions (MCQs) with one correct answer and three incorrect answers.
- Interactive session to display MCQs and receive user input.

## Installation

### Requirements

- Python 3.7 or higher
- Pip package manager

### Install Required Libraries

```bash
pip install pytube openai-whisper transformers torch sentence-transformers
