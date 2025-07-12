## Health Sensing : Internship Selection Task 
Sustainability Lab – IIT Gandhinagar

This project is part of an internship assignment for the Sustainability Lab at Indian Institute of Technology Gandhinagar (IITGN). The task involves building a pipeline to detect breathing irregularities and classify sleep stages using physiological signals recorded during overnight sleep sessions.

## Objectives

📈 Visualize physiological signals: nasal airflow, thoracic movement, and SpO₂

🔎 Detect breathing anomalies such as Apnea and Hypopnea

😴 Classify sleep stages: Wake, N1, N2, N3, REM

🧠 Train deep learning models using subject-wise validation

🧼 Filter noise and structure clean, labeled datasets for modeling

## Folder Structure

Project Root/
├── Data/              
│   └── AP01/
│       ├── nasal_airflow.txt
│       ├── thoracic_movement.txt
│       ├── spo2.txt
│       ├── flow_events.csv
│       └── sleep_profile.csv
│
├── Visualizations/          # Multi-page signal PDFs
├── Dataset/                 # Preprocessed datasets (CSV)
├── models/                  # CNN and Conv-LSTM architectures
├── scripts/                 # All preprocessing, plotting, modeling scripts
├── run_pipeline.ipynb       # Full notebook to demonstrate the pipeline
├── requirements.txt         # All Python dependencies
└── report.pdf               # (Optional) Final summary report


## Outputs

🖼️ PDF signal visualizations: Visualizations/AP01_visualization.pdf, etc.

📁 Labeled window datasets:

breathing_dataset.csv – Normal, Hypopnea, Obstructive Apnea

sleep_stage_dataset.csv – Wake, REM, N1, N2, N3

🤖 Training logs and metrics (precision, recall, accuracy)

## Models Used

Task	Model
Breathing Irregularity Detection	1D CNN
Sleep Stage Classification	Conv-LSTM

Validation is done via Leave-One-Participant-Out Cross Validation to avoid data leakage.

## Requirements

Python >= 3.8

pip install -r requirements.txt

## Project Summary

This project was developed as part of the Health Sensing Internship Assignment under the guidance of the Sustainability Lab, IIT Gandhinagar.
It demonstrates practical application of data preprocessing, time-series analysis, deep learning, and domain-specific modeling for sleep-related health monitoring.


## 📌 Author
Aakanksha Tiwari
Sustainability Lab – Internship Application
GitHub Profile


