# EEG-Based Emotion & Discomfort Detection System

This project proposes a machine learning system that uses EEG brain signals to detect and classify emotions in non-verbal patients. The system performs multi-class emotion classification using the DEAP dataset, employing a multi-scale dynamic CNN with gated transformer architecture. By categorizing emotional states into four classes based on valence and arousal dimensions, the system aims to provide healthcare professionals with real-time, granular insights into patients’ emotional states, significantly improving care for individuals with locked-in syndrome, severe paralysis, and related conditions.

## Overview

- **Stage 1**: Emotion classification (4 classes: LVLA, LVHA, HVLA, HVHA) using DEAP dataset
- **Stage 2**: Motor imagery classification (4 classes: Left Hand, Right Hand, Feet, Tongue) using BCI Competition IV-2a dataset

## Datasets

1. **DEAP Dataset**: Download from [DEAP website](http://www.eecs.qmul.ac.uk/mmv/datasets/deap/) and place in `data_preprocessed_python/`
2. **BCI Competition IV-2a**: Download from [GitHub](https://github.com/bregydoc/bcidatasetIV2a) and place in `bcidatasetIV2a/`


## Usage

Run the notebook in Google Colab or locally:

```bash
jupyter notebook EEG_Based_Emotion_Discomfort_Detection_System_for_Non_Verbal_Patients.ipynb
```

## Results

- Emotion Classification: 64.87% accuracy
- Motor Imagery Classification: 65.6% accuracy

## Models

- **MSDCGTNet**: Multi-Scale Dynamic CNN with Gated Transformer for emotion classification
- **MotorImageryNet**: EEGNet-based architecture for motor imagery classification

