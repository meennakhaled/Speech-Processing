# Speech Processing and CNN

This repository contains implementations for audio signal processing, speech analysis, and deep learning-based spoken digit recognition using CNN models.

The project is divided into three main assignments:

- A1: WAV File Processing
- A2: Speech Signal Analysis
- A3: Spoken Digit Recognition using CNN

---

# Assignment 1 — WAV File Processing

## Tasks
- Read a `.wav` audio file
- Extract:
  - Sampling Rate
  - Bit Rate
  - Data Size (bits & bytes)
  - Total Number of Samples
  - Audio Type (Mono/Stereo)
- Reverse the audio signal
- Save the reversed signal as a new `.wav` file

---

# Assignment 2 — Speech Signal Analysis

## Tasks
- Read two `.wav` files:
  - Voice signal
  - Non-voice signal
- Apply framing on both signals
- Calculate total number of frames
- Display the first 20 frames
- Apply:
  - Hamming Window
  - Hanning Window
- Compute:
  - Zero Crossing Rate (ZCR)
  - Energy for each frame
- Plot:
  - Zero Crossing Rate
  - Energy curves

---

# Assignment 3 — Spoken Digit Recognition

## Dataset
TensorFlow Spoken Digit Dataset

## Tasks
- Split dataset into:
  - Training Set
  - Validation Set
  - Test Set
- Extract MFCC features
- Build:
  - 2D CNN using MFCC features
  - 1D CNN using raw audio signals
- Handle variable-length audio samples
- BONUS:
  - Plot spectrograms

---
