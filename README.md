# Speech-Emotion-Recognition

<p>In this Project we are using LDA to recognize the emotion of any audio speech in Python. The dataset used contains 1140 sound files in which 24 actors recorded their voice for 8 different emotions. The project  uses multiple modules for emotion recognition and classiﬁers to discriminate emotions like anger, neutral state, happiness, surprise, sadness, and so on. The voice samples are used as the data set for the "speech emotion recognition system," and the characteristics are retrieved from these speech samples using the LIBROSA software. The performance of categorization is based on extracted features. Finally, the emotion of a voice signal can be determined.</p>

Basic Idea :<br>
Our machine learning model tries to detect and predict various emotion in speech signal or human audio by detecting different features and component of speech affected by human emotion. Emotion detection from the speech is a relatively new field of research. Here, we are trying a new approach or ways to contribute towards emotion recognition research.

<img src="Speech Emotion Recognition.gif" alt="Figure 1. Speech Emotion Recognition Web App " >


## Dataset

Link to the dataset used in our project is [here](https://zenodo.org/record/1188976/files/Audio_Speech_Actors_01-24.zip?download=1)

## Limitation and Further growth
1. Need to record audio in clear and silent environment.
2. Dataset is not accurate and prominant. Even, human ear can't detect accurate emotion for some audios. **Need Promising dataset.**

## Emotions available
There are 3 emotions available: "neutral", "happy" & "angry"

## Feature Extraction
Feature extraction is the main part of the speech emotion recognition system. It is basically accomplished by changing the speech waveform to a form of parametric representation at a relatively lesser data rate.

In this repository, we have used the most used features that are available in [librosa](https://github.com/librosa/librosa) library including:
- [MFCC](https://en.wikipedia.org/wiki/Mel-frequency_cepstrum)
- Chromagram 
- MEL Spectrogram Frequency (mel)
- Tonnetz (tonal centroid features)

## How to run file :
To implement this project on your Machine
1. Clone this repository.
2. Go to terminal and type `pip install -r requirements.txt`.
3. Then open main_speech_emotion_recognition.ipynb and run it.
