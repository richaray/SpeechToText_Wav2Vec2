# 🎙️ Speech-to-Text Converter using Wav2Vec2

A deep learning-based Speech-to-Text (STT) system built using Meta's Wav2Vec2 model for automatic speech recognition (ASR). The project leverages the LJ Speech dataset for training and evaluation, enabling accurate transcription of spoken audio into text.

Audio preprocessing and feature extraction were performed using Librosa, while the Wav2Vec2 architecture was fine-tuned to learn robust speech representations and generate high-quality transcriptions.

## Demo Video



https://github.com/user-attachments/assets/1ebe47bb-5c57-47c6-86bc-59949662613d



## 🚀 Features

* 🎤 Convert speech audio into text automatically
* 🧠 Powered by the Wav2Vec2 transformer-based ASR model
* 🔊 Audio preprocessing using Librosa
* 📚 Trained and evaluated on the LJ Speech Dataset
* 📈 Supports model fine-tuning and performance evaluation
* ⚡ End-to-end speech recognition pipeline

## 🛠️ Tech Stack

* Python
* PyTorch
* Hugging Face Transformers
* Wav2Vec2
* Librosa
* NumPy
* Pandas
* Jupyter Notebook

## 📊 Dataset

**LJ Speech Dataset**

* Single-speaker English speech dataset
* 13,000+ audio clips
* Approximately 24 hours of speech data
* High-quality transcriptions for supervised learning

## 🔄 Workflow

1. Load and preprocess audio files.
2. Extract and normalize audio features using Librosa.
3. Tokenize transcriptions and prepare training data.
4. Fine-tune the Wav2Vec2 model on the LJ Speech dataset.
5. Evaluate model performance on validation data.
6. Generate text transcriptions from unseen audio samples.

## 🎯 Applications

* Voice assistants
* Automated transcription services
* Accessibility tools
* Speech analytics systems
* Customer support automation

## 🔮 Future Enhancements

* Support for real-time speech recognition
* Multi-speaker transcription
* Noise-robust audio processing
* Deployment as a web application
* Support for multiple languages

## 📜 Results

The model successfully learns speech representations from raw audio and generates accurate text transcriptions, demonstrating the effectiveness of transformer-based architectures for automatic speech recognition tasks.
