# Voice Activity Detection Using Machine Learning and Audio Signal Processing

## Project Overview

This project implements a machine learning-based Voice Activity Detection system that identifies whether an audio segment contains human speech or silence.

Voice Activity Detection, commonly called VAD, is an important component of speech-processing systems such as:

- Speech recognition
- Voice assistants
- Audio transcription
- Call-center analytics
- Speaker diarization
- Meeting transcription
- Noise reduction
- Voice-controlled applications

The system accepts an uploaded ZIP file containing audio files, extracts the dataset, processes the audio, extracts acoustic features, trains a Random Forest classifier, evaluates the model, and detects speech segments in an audio file.

---

## Project Objective

The main objective of this project is to build an end-to-end Voice Activity Detection pipeline that can:

1. Accept an audio dataset in ZIP format.
2. Extract audio files automatically.
3. Load and preprocess audio files.
4. Extract frame-level audio features.
5. Generate speech and silence training samples.
6. Train a machine learning classification model.
7. Evaluate model performance.
8. Detect speech segments from an audio file.
9. Generate speech timestamps.
10. Save speech-only audio output.

---

## Features

- ZIP dataset upload support
- Automatic ZIP extraction
- Support for WAV, MP3, FLAC, OGG, and M4A files
- Audio resampling to 16 kHz
- Mono audio conversion
- Frame-level feature extraction
- Speech and silence classification
- Random Forest machine learning model
- Accuracy, precision, recall, and F1-score evaluation
- Confusion matrix visualization
- Feature importance analysis
- Speech timestamp generation
- Speech-only audio generation
- Automatic saving of trained model and output files
- Google Colab compatible implementation

---

## Technologies Used

### Programming Language

- Python

### Libraries

- NumPy
- Pandas
- Librosa
- SoundFile
- Scikit-learn
- SciPy
- Matplotlib
- Joblib

### Development Environment

- Google Colab
- Jupyter Notebook
- Python 3

---

## System Architecture

```text
Upload ZIP Dataset
        |
        v
Extract Audio Files
        |
        v
Audio Preprocessing
        |
        v
Feature Extraction
        |
        v
Create Speech and Silence Labels
        |
        v
Train-Test Split
        |
        v
Random Forest Model Training
        |
        v
Model Evaluation
        |
        v
Speech Detection
        |
        v
Speech Timestamps and Speech-Only Audio
