# Emotion-Recognition

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/-Machine%20Learning-orange)
![Audio Processing](https://img.shields.io/badge/-Audio%20Processing-green)

This repository contains an emotion recognition system developed on 2,300+ WAV files using acoustic feature extraction and machine learning techniques.

## Project Overview

This project implements an emotion recognition system that classifies audio files into 15 emotion categories. The system uses Parselmouth for acoustic feature extraction and SVM for classification, achieving 72% accuracy with a 0.68 F1-score using leave-one-speaker-out cross validation.

## Features

- Extracts 6 key acoustic features including:
  - Pitch statistics (mean, median, std dev)
  - Intensity statistics (mean, median, std dev)
- Z-score normalization for feature standardization
- Support Vector Machine (SVM) classifier
- Leave-one-speaker-out cross validation
- Emotion classification across 15 classes

## Tech Stack

### Core Technologies
- **Python 3.8+**
- **Parselmouth** - For acoustic feature extraction from WAV files
- **openSMILE** - For feature vector extraction
- **scikit-learn** - For SVM implementation and model evaluation
- **Librosa** - For audio processing and analysis
- **NumPy/Pandas** - For data manipulation and analysis
- **Matplotlib/Seaborn** - For visualization

