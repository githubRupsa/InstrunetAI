# 🎵 InstruNet AI: Music Instrument Recognition System

[cite_start]**InstruNet AI** is a Deep Learning-based system designed to automatically detect instruments in music tracks by applying Convolutional Neural Networks (CNNs) to audio spectrograms[cite: 5]. [cite_start]This project automates the labeling process, which is traditionally time-consuming and error-prone[cite: 4].

## 🚀 Overview
[cite_start]InstruNet AI converts raw audio files into visual spectrogram representations and uses a trained **ResNet18** model to identify the presence and intensity of specific musical instruments[cite: 7, 8, 48].

## 🛠️ Technology Stack
* **Programming Language:** Python 3 
* **Audio Processing:** Librosa
* **Deep Learning Framework:** PyTorch (torchvision)
* **Visualization:** Matplotlib, Seaborn 
* **Dashboard:** Streamlit 
* **Dataset:** NSynth Dataset

## 🏗️ System Architecture
[cite_start]The system follows a modular end-to-end pipeline[cite: 45]:
1.  [cite_start]**Audio Input Module:** Accepts MP3/WAV files, converts them to mono, and normalizes them[cite: 46].
2.  [cite_start]**Preprocessing Unit:** Generates Mel-spectrograms from the audio signal[cite: 47].
3.  [cite_start]**CNN Model:** A ResNet18 architecture classifies spectrogram images to predict instrument labels[cite: 33, 48].
4.  [cite_start]**Post-Processing:** Applies thresholding to probabilities for final detection[cite: 37, 49].
5.  [cite_start]**Output Module:** Displays results on an interactive dashboard with intensity visualizations and exports reports[cite: 40, 50].



## 📊 Key Features
* [cite_start]**Interactive Dashboard:** Real-time visualization of spectrograms and instrument intensity bars[cite: 10, 54].
* [cite_start]**Multi-Class Detection:** Capable of identifying instruments like piano, guitar, drums, and more[cite: 14, 71].
* [cite_start]**Automated Reporting:** Generates track analysis reports in **JSON** and **PDF** formats[cite: 11, 24].

## 📈 Two-Month Milestone Plan
[cite_start]This project was completed according to a structured timeline[cite: 100]:
* [cite_start]**Weeks 1-2:** Data Collection & Preprocessing (Mel-spectrogram generation)[cite: 101].
* [cite_start]**Weeks 3-4:** CNN Model Development (ResNet18 baseline training)[cite: 105].
* [cite_start]**Weeks 5-6:** Model Evaluation & Hyperparameter Tuning[cite: 109].
* [cite_start]**Weeks 7-8:** Deployment & Visualization (Streamlit web app & report generation)[cite: 114].

---

## 👨‍💻 Author
**[RUPSA PAL](https://github.com/githubRupsa)**
*CSE (AIML) Student*
[cite_start]Developed as an end-to-end pipeline for instrument recognition and visualization[cite: 123].

---

### How to Run Locally
1.  Clone the repository: `git clone https://github.com/githubRupsa/InstrunetAI.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Launch the dashboard: `streamlit run app1.py`
