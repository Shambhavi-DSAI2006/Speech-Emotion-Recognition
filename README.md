#  Speech Emotion Recognition using Machine Learning & Deep Learning

An end-to-end **Speech Emotion Recognition (SER)** system that classifies human emotions from speech using Machine Learning and Deep Learning techniques. This project leverages the **RAVDESS** and **CREMA-D** benchmark datasets and explores model optimization through **pruning**, **quantization**, **Principal Component Analysis (PCA)**, and **K-Means coreset selection** to improve computational efficiency while maintaining predictive performance.

---

##  Overview

Speech Emotion Recognition (SER) is a challenging task in speech processing that aims to identify the emotional state of a speaker from audio signals. Accurate emotion recognition has applications in human-computer interaction, virtual assistants, healthcare, customer service, and affective computing.

This project implements a complete SER pipeline, beginning with raw audio preprocessing and feature extraction, followed by training and evaluating multiple Machine Learning and Deep Learning models. It further investigates model compression techniques to reduce model size and inference cost without significantly compromising accuracy.

---

##  Key Features

* Audio preprocessing and normalization
* MFCC-based feature extraction
* Exploratory Data Analysis (EDA)
* Classical Machine Learning models

  * Support Vector Machine (SVM)
  * Logistic Regression
  * Random Forest
* Deep Learning using Multi-Layer Perceptron (MLP)
* Model optimization techniques

  * Gradual Magnitude Pruning (GMP)
  * INT8 Quantization
  * Principal Component Analysis (PCA)
  * K-Means Coreset Selection
* Performance evaluation using standard classification metrics

---

##  Datasets

This project uses two publicly available benchmark datasets.

### RAVDESS

**Ryerson Audio-Visual Database of Emotional Speech and Song**

* 24 professional actors
* 8 emotion classes
* High-quality emotional speech recordings

### CREMA-D

**Crowd-sourced Emotional Multimodal Actors Dataset**

* 91 actors
* 6 emotion classes
* Diverse speech samples with varying emotional intensities

> **Note:** The datasets are **not included** in this repository due to licensing restrictions and repository size limitations. Please download them from their official sources before running the project.

---

## ⚙️ Tech Stack

| Category             | Technologies  |
| -------------------- | ------------- |
| Programming Language | Python        |
| Audio Processing     | Librosa       |
| Data Analysis        | NumPy, Pandas |
| Machine Learning     | Scikit-learn  |
| Deep Learning        | PyTorch       |
| Visualization        | Matplotlib    |
| Model Serialization  | Joblib        |

---

##  Repository Structure

```text
Speech-Emotion-Recognition/
│
├── datasets/
│   └── README.md
│
├── notebooks/
│   ├── RAVDESS_D2_Deliverable.ipynb
│   ├── CREMAD_D2_Deliverable_2.ipynb
│   └── Deliverable_3.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── feature_extraction.py
│   ├── models.py
│   ├── train.py
│   ├── evaluate.py
│   └── utils.py
│
├── saved_models/
│
├── results/
│
├── reports/
│
├── images/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

##  Project Workflow

```text
Raw Audio Files
        │
        ▼
Audio Preprocessing
        │
        ▼
MFCC Feature Extraction
        │
        ▼
Feature Engineering
        │
        ▼
Train/Test Split
        │
        ▼
Machine Learning Models
(SVM, Logistic Regression, Random Forest)
        │
        ▼
Deep Learning Model (MLP)
        │
        ▼
Model Optimization
• Pruning
• Quantization
• PCA
• K-Means Coreset Selection
        │
        ▼
Performance Evaluation
```

---

##  Evaluation Metrics

Model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

##  Getting Started

### Clone the Repository

```bash
git clone https://github.com/<your-username>/Speech-Emotion-Recognition.git
cd Speech-Emotion-Recognition
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Download the Datasets

Download the RAVDESS and CREMA-D datasets from their official websites and place them inside the `datasets/` directory.

### Run the Project

Execute the notebooks in the `notebooks/` directory or use the Python scripts in the `src/` directory to reproduce the experiments.

---

##  Results

This project compares the performance of multiple Machine Learning and Deep Learning models on benchmark speech emotion datasets while analyzing the impact of model compression techniques.

The repository includes:

* Training and validation results
* Confusion matrices
* Performance comparison plots
* Compression analysis
* Experimental reports

---

##  Future Work

Potential improvements include:

* Convolutional Neural Networks (CNN)
* CNN-LSTM hybrid architectures
* Transformer-based speech models
* Wav2Vec 2.0 embeddings
* Real-time speech emotion recognition
* Web deployment using Streamlit or Flask

---

##  Authors

**Shambhavi Srivastava**

**Yashash**

---

##  License

This project is licensed under the MIT License.

---

##  Acknowledgements

* RAVDESS Dataset
* CREMA-D Dataset
* Librosa
* PyTorch
* Scikit-learn
* Open-source research community for speech processing resources
# Speech-Emotion-Recognition
Speech Emotion Recognition using Machine Learning and Deep Learning on the RAVDESS and CREMA-D datasets, with model compression techniques including pruning, quantization, PCA, and coreset selection.
