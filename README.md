# Biomedical Signal Processing & Anemia Prediction Models

This repository contains a collection of biomedical signal processing pipelines and machine learning models developed for physiological data analysis.

The project focuses on three main components:

1. PPG (Photoplethysmography) Signal Processing Pipeline  
2. EMG (Electromyography) Signal Processing  
3. Machine Learning Models for Anemia Prediction based on Hemoglobin levels  

---

## 🔬 1. PPG Processing Pipeline

The PPG pipeline includes:

- Signal acquisition handling
- Noise reduction using digital filters
- Baseline drift removal
- Peak detection
- Feature extraction (heart rate, amplitude, etc.)
- Frequency domain analysis (FFT)

The objective is to obtain clean and clinically relevant cardiovascular features from raw PPG signals.

---

## 💪 2. EMG Signal Processing

The EMG module includes:

- Band-pass filtering
- Signal rectification
- RMS and envelope extraction
- Muscle activation analysis
- Time-domain feature extraction

This pipeline is designed to analyze muscle activity patterns and reduce motion artifacts.

---

## 🩸 3. Anemia Prediction Model

This section implements machine learning models to predict anemia using hemoglobin-related parameters.

Workflow:

- Data preprocessing
- Feature scaling
- Model training (classification/regression depending on dataset)
- Performance evaluation
- Accuracy and error analysis

The goal is to explore predictive modeling for early anemia detection using physiological markers.

---

## 🛠 Technologies Used

- Python
- NumPy
- SciPy
- Matplotlib
- scikit-learn
- Jupyter Notebook

---

## 📊 Project Motivation

Biomedical signals are often noisy and complex. This repository demonstrates structured pipelines for transforming raw physiological data into meaningful diagnostic insights using signal processing and machine learning techniques.

---

## 🚀 Future Improvements

- Real-time signal processing implementation
- Deep learning-based anemia prediction
- Integration of multimodal signals (PPG + EMG)
- Deployment as a lightweight diagnostic tool

---

## 📌 Author

Mayank Sarvpriya  
Engineering Student | Biomedical Signal Processing & AI Enthusiast

