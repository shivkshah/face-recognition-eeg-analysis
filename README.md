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
    ```

2. (Optional) Create and activate a virtual environment:

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # For Windows: venv\Scripts\activate
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the analysis notebook:

    ```bash
    jupyter notebook code/analysis_notebook.ipynb
    ```

## Notes

- Large EEG data files are excluded from the repo due to GitHub file size limits.
- You'll need to manually add your `.fdt` and `.set` files to the `data/` folder before running the notebook.

## Author

Shiv Shah  
Neuroscience @ UT Austin  
[GitHub Profile](https://github.com/shivkshah)
