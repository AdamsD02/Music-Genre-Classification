# Music-Genre-Classification

## 📄 Problem Statement 
Description: Develop a machine learning model to classify music clips into genres such as rock, jazz, or classical using audio features like tempo or spectral characteristics. 

Suggested Dataset: GTZAN Genre Collection or Free Music Archive (FMA). 

Tools: Python, Librosa, Scikit-learn.

---

## 🎶 Music Genre Detection App

This is a web app built with **Flask** that lets users upload an audio file and returns the predicted **music genre** using audio feature extraction and machine learning.

### 🚀 Features

- Upload any audio file through a web form
- Automatic feature extraction using `librosa`
- Genre prediction using a LightGBM-trained model
- Deployed in Google Colab using `ngrok`

---
## ⚙️ Working

- Train LightGBM Model using the **feature_30_sec.csv** file
- Audio file can be uploaded using either **Google Colab's `files` module** or **Web interface** created using `Flask` and `ngrok`
- Uses `librosa` to extract **features** from audio like mfcc, chroma-stft, zero-crossing-rate, etc.
- Passes features to a trained model
- Returns the predicted music genre

*Note: The app runs only while the Colab notebook is active.*

---
## Contents 
- README.md
- feature_30_sec.csv
- mgc_code.ipynb
- genres (directory)

*Note: the genres folder contains audio files of different genres which can be used to test implementation.*
