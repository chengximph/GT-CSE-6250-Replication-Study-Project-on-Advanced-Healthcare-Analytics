# GT-CSE-6250-Replication-Study-Project-on-Advanced-Healthcare-Analytics

# Overview

This repository contains all the necessary code, data, and documentation for the replication study of the LSTM-based model for early sepsis prediction, as introduced in the GT CSE 6250 course. Our study focuses on validating the predictive accuracy, interpretability, and handling of irregular time intervals by the model.

# Project Structure
.
├── data/                   # Folder for datasets used in the project
├── src/                    # Source code for the replication study
│   ├── preprocessing/      # Data preprocessing scripts
│   ├── training/           # Model training scripts
│   ├── evaluation/         # Evaluation and analysis scripts
│   └── utils/              # Utility scripts and functions
├── models/                 # Trained model files and configuration
├── results/                # Output results and figures
├── requirements.txt        # Python dependencies
└── README.md               # Documentation of the project

To install the required Python packages, run:

pip install -r requirements.txt

# Data

The dataset is derived from the Cerner Health Facts database and accessed via the original authors' GitHub page. Due to privacy constraints, the full dataset is not publicly available. The data folder includes a sample of the final cohort used for our analyses.

# Usage

Data Preprocessing
To preprocess the data, navigate to the src/preprocessing directory and execute:
python preprocess.py

Model Training
To train the LSTM model, navigate to the src/training directory and execute:
python train.py

Evaluation
To evaluate the model and generate results, navigate to the src/evaluation directory and execute:
python evaluate.py

# Contributing

We welcome contributions and suggestions to improve the replication study. Please submit pull requests or open issues for any enhancements you propose.

# Acknowledgements
Thanks to the instructors and contributors of the GT CSE 6250 course for providing the foundation for this replication study.
