# Speech Preprocessing Pipeline – LibriSpeech

This project implements a complete voice preprocessing workflow for speech data.

## Preprocessing Steps
- Audio loading
- Resampling to 16 kHz
- Normalization
- Silence trimming
- Low-pass filtering

## Feature Extraction
- Log Mel Spectrograms

## Output
Final feature tensor shape:
[2, 1, 64, time_frames]

## Purpose
Prepare speech data for machine learning and deep learning models.
