# face-recognition-eeg-analysis
# Face Recognition EEG Analysis

This project analyzes EEG data recorded during a face recognition task. The goal is to compare neural responses to human faces versus scrambled images using Python and MNE-Python.

## Contents

- Preprocessing EEG data
- Epoching around stimulus events
- ERP analysis and statistical comparison
- Visualization of results

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/shivkshah/face-recognition-eeg-analysis.git
   cd face-recognition-eeg-analysis
python3 -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook code/analysis_notebook.ipynb
