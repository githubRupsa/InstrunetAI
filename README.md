# 🎵 InstruNet AI: Music Instrument Recognition System

**InstruNet AI** is a Deep Learning-based system designed to automatically detect instruments in music tracks by applying Convolutional Neural Networks (CNNs) to audio spectrograms. This project automates the labeling process, which is traditionally time-consuming and error-prone.

## 🚀 Overview
InstruNet AI converts raw audio files into visual spectrogram representations and uses a trained **ResNet18** model to identify the presence and intensity of specific musical instruments.

## 🛠️ Technology Stack
* **Programming Language:** Python 3 
* **Audio Processing:** Librosa
* **Deep Learning Framework:** PyTorch (torchvision)
* **Visualization:** Matplotlib, Seaborn 
* **Dashboard:** Streamlit 
* **Dataset:** NSynth Dataset

## 🏗️ System Architecture
The system follows a modular end-to-end pipeline:
1.  **Audio Input Module:** Accepts MP3/WAV files, converts them to mono, and normalizes them.
2.  **Preprocessing Unit:** Generates Mel-spectrograms from the audio signal.
3.  **CNN Model:** A ResNet18 architecture classifies spectrogram images to predict instrument labels.
4.  **Post-Processing:** Applies thresholding to probabilities for final detection.
5.  **Output Module:** Displays results on an interactive dashboard with intensity visualizations and exports reports.



## 📊 Key Features
* **Interactive Dashboard:** Real-time visualization of spectrograms and instrument intensity bars.
* **Multi-Class Detection:** Capable of identifying instruments like piano, guitar, drums, and more.
* **Automated Reporting:** Generates track analysis reports in **JSON** and **PDF** formats.

## 📈 Two-Month Milestone Plan
This project was completed according to a structured timeline:
* **Weeks 1-2:** Data Collection & Preprocessing (Mel-spectrogram generation).
* **Weeks 3-4:** CNN Model Development (ResNet18 baseline training).
* **Weeks 5-6:** Model Evaluation & Hyperparameter Tuning.
* **Weeks 7-8:** Deployment & Visualization (Streamlit web app & report generation).

---

## 👨‍💻 Author
**[RUPSA PAL](https://github.com/githubRupsa)**
*CSE (AIML) Student*
Developed as an end-to-end pipeline for instrument recognition and visualization[cite: 123].

---

### How to Run Locally
1.  Clone the repository: `git clone https://github.com/githubRupsa/InstrunetAI.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Launch the dashboard: `streamlit run app1.py`
