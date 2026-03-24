# Brugada ECG · AI Detector

AI-powered web dashboard for detecting Brugada Syndrome from 12-lead ECG recordings.

## Pipeline
EDF/wfdb → Bandpass Filter → R-Peak Detection → SVM Classification

## Features
- Load from PhysioNet Brugada dataset or upload .hea/.dat
- Interactive signal visualization
- Beat-level prediction with probability chart
- Export results as CSV

## Tech Stack
Python · Streamlit · wfdb · NeuroKit2 · scikit-learn · SciPy

## Dataset
PhysioNet Brugada-HUCA 12-lead ECG dataset
https://physionet.org/content/brugada-huca/1.0.0/

## Run
streamlit run app.py
