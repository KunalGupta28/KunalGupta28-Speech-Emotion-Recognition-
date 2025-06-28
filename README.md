# KunalGupta28-Speech-Emotion-Recognition-
🎙️ Speech Emotion Recognition using CNN — A deep learning project that detects emotions (happy, sad, angry, etc.) from speech audio using MFCC features and a Convolutional Neural Network. Ideal for sentiment analysis, virtual assistants, and HCI systems.
# 🎙️ Speech Emotion Recognition using CNN

This project is a deep learning-based **Speech Emotion Recognition (SER)** system that detects emotions such as **happy**, **sad**, **angry**, **calm**, and more from human speech audio. It uses **MFCC (Mel-Frequency Cepstral Coefficients)** for feature extraction and a **Convolutional Neural Network (CNN)** for classification.

---

## 🧠 Overview

- Preprocesses `.wav` audio files from multiple datasets.
- Extracts MFCC features for audio representation.
- Trains a CNN model to classify speech emotions.
- Evaluates performance with accuracy/loss plots.
- Saves the trained model for reuse.

---

## 📁 Datasets Used

This project combines multiple publicly available datasets for better generalization and robust emotion detection:

1. **[RAVDESS](https://zenodo.org/record/1188976)**  
   Ryerson Audio-Visual Database of Emotional Speech and Song.

2. **[TESS](https://dataverse.library.yorku.ca/dataset.xhtml?persistentId=doi:10.5683/SP2/E8H2MF)**  
   Toronto Emotional Speech Set — contains recordings of 2 female actors saying target words in 7 emotions.

3. **[SAVEE](https://github.com/atulapra/Emotion-detection/blob/master/README.md#datasets)**  
   Surrey Audio-Visual Expressed Emotion — includes recordings from 4 male speakers across 7 emotions.

4. **[CREMA-D](https://github.com/CheyneyComputerScience/CREMA-D)**  
   Crowd-Sourced Emotional Multimodal Actors Dataset — recordings from 91 actors with validated emotion labels.

---

## 📦 Installation

```bash
git clone https://github.com/KunalGupta28/KunalGupta28-Speech-Emotion-Recognition-.git
cd speech-emotion-recognition
pip install -r requirements.txt
