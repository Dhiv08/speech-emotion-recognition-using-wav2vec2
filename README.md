### speech-emotion-recognition-using-wav2vec2


This project implements **Speech Emotion Recognition (SER)** using **Wav2Vec2**, a pre-trained transformer-based model for speech processing. The model classifies emotions from audio recordings into categories such as *Happy, Sad, Angry, Fear, Neutral, Disgust, and Surprise*.

##  Features
✅ Uses **Wav2Vec2** for feature extraction and classification  
✅ Supports **seven emotion classes**  
✅ Implements **waveplot and spectrogram visualization**  
✅ Fine-tuned using **Hugging Face Transformers**  
✅ Works with **Librosa** for audio processing  

---

##  Installation & Setup

### 1️) **Clone the Repository**

### 2) Required Dependencies
pandas
numpy
os-sys
seaborn
matplotlib
librosa
ipython
torchaudio
torch
transformers
datasets

### 3)Download Dataset
https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess

### 3)Run the Notebook
jupyter notebook

### How It Works

### 1️) Load & Preprocess Data
Audio files are loaded using Librosa
Labels are converted into integer class mappings

### 2️) Feature Extraction with Wav2Vec2
Facebook’s Wav2Vec2 is used to extract features from speech
The extracted features are passed to a classifier

### 3️) Model Training & Evaluation
Model fine-tunes Wav2Vec2 using PyTorch & Hugging Face Transformers
Evaluates model performance with accuracy, F1-score, and loss metrics

### 4️) Inference & Prediction
Trained model predicts the emotion in new audio files


