# VCC26 Traffic Sign Classifier
Lawrence Technological University — HW6 Class Competition

## Overview
Real-time traffic sign classification using VGG16 with webcam 
and Text-to-Speech output. Built for the Robofest 2026 Vision 
Challenge Competition.

## Model
- Architecture: VGG16 with Feature Extraction and Fine Tuning (FE2FineT)
- Input size: 224 x 224
- Training: Two phase training with data augmentation

## Files
- vcc26_training.ipynb      - Training pipeline
- vcc26_competition.ipynb   - Real-time webcam inference app

## How to Run
1. Open vcc26_training.ipynb in Google Colab
2. Mount your Google Drive
3. Update BASE_DIR to your dataset path
4. Run all cells in order
5. Open vcc26_competition.ipynb
6. Run all cells in order
7. Click Start Webcam

## Dataset
Dataset is stored privately on Google Drive and not included in this repo.

## Results
- Test Accuracy: 97.98 %
