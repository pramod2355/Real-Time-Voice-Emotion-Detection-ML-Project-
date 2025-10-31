# Real-Time Voice Emotion Detection

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![GitHub LFS](https://img.shields.io/badge/Git-LFS-blue)

---

## Project Description

The **Real-Time Voice Emotion Detection** project is a Python-based system that **detects emotions from voice input in real time**.
It analyzes audio signals and classifies emotions such as:

* **Happy**
* **Sad**
* **Angry**
* **Neutral**
* **Surprise**
* **Fear**
* **Disgust**

This system can be used in applications like **human-computer interaction, virtual assistants, healthcare, emotion-aware systems, and call-center monitoring**.

---

## Features

* Real-time detection from microphone input.
* Preprocessing of audio files using MFCC (Mel Frequency Cepstral Coefficients).
* Classification using machine learning/deep learning models.
* Handles `.wav` audio files.
* Visual feedback for detected emotions.
* Supports Git LFS for large dataset files.

---

## Project Structure

```
Real-Time-Voice-Emotion-Detection/
├── data/
│   ├── raw/                   # Original audio dataset
│   └── processed/             # Preprocessed features (X.npy, y.npy, le_classes.npy)
├── models/                    # Trained ML/DL models
├── scripts/                   # Python scripts for preprocessing, training, testing
│   ├── preprocess.py
│   ├── train_model.py
│   └── test_real_time.py
├── README.md
└── requirements.txt           # Python dependencies
```

---

## Demo

![Demo GIF](https://user-images.githubusercontent.com/yourusername/demo.gif)

> The system listens to your microphone and displays the predicted emotion in real-time.

---

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/Sai0045/ML-Project.git
cd ML-Project
```

2. **Install Git LFS** (for large `.npy` files)

```bash
git lfs install
git lfs pull
```

3. **Create a virtual environment**

```bash
python -m venv venv
```

4. **Activate the environment**

* Windows:

```bash
venv\Scripts\activate
```

* Linux / Mac:

```bash
source venv/bin/activate
```

5. **Install dependencies**

```bash
pip install -r requirements.txt
```

---

## Usage

### 1. Preprocess audio data

```bash
python scripts/preprocess.py
```

### 2. Train the model

```bash
python scripts/train_model.py
```

### 3. Real-time emotion detection

```bash
python scripts/test_real_time.py
```

> Make sure your microphone is connected for real-time testing.

---

## Dependencies

* Python 3.8+
* NumPy
* pandas
* scikit-learn
* librosa
* TensorFlow / PyTorch (depending on the model)
* matplotlib
* Git LFS

---

## Dataset

* Original audio dataset is stored in `data/raw/`.
* Preprocessed dataset features (`X.npy`, `y.npy`, `le_classes.npy`) are stored in `data/processed/`.
* Large `.npy` files are tracked using **Git LFS**.

> Git LFS ensures files larger than 100 MB can be pushed to GitHub.

---

## Notes

* For best results, ensure your environment matches the required dependencies.
* You can retrain the model with your own dataset if desired.
* Real-time detection may have slight delays depending on CPU/GPU performance.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## References

* [Librosa Documentation](https://librosa.org/)
* [Git Large File Storage (LFS)](https://git-lfs.github.com/)
* Research papers on voice emotion recognition using machine learning and deep learning.

---

## Author

**Sairaj Abhale**
Email: [[sairajabhale@gmail.com](mailto:sairajabhale@gmail.com)]
GitHub: [https://github.com/Sai0045](https://github.com/Sai0045)

**Akshay Kharpas,**
**Swadesh Turkane,**
**Pramod Khalkar**


