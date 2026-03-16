# AI-Based Log Investigation System

An AI-powered cybersecurity project that analyzes Windows system logs to automatically detect suspicious activity and potential threats.  
The system uses machine learning models to classify log entries and assist in digital forensic investigation.

---

## Project Overview

Modern systems generate massive volumes of logs that make manual analysis difficult.  
This project applies machine learning techniques to automatically analyze Windows logs and detect abnormal or malicious activity.

The goal is to assist **Security Operations Center (SOC) analysts** by reducing manual investigation effort and highlighting suspicious patterns.

---

## Features

- Automated Windows log analysis
- Machine learning-based threat detection
- Detection of abnormal system activities
- Interactive investigation interface using Gradio
- CSV log ingestion and processing
- Model-based classification of log events

---

## Project Architecture


Log Files → Feature Extraction → ML Model → Threat Detection → Investigation Dashboard


---

## Folder Structure


AI_based_log_investigation
│
├── models/
│ ├── windows_threat_detection_model.pkl
│ └── label_encoder.pkl
│
├── data/
│ └── windows_log_dataset.csv
│
├── notebooks/
│ └── training_notebook.ipynb
│
├── app.py
├── requirements.txt
└── README.md


---

## Technologies Used

- Python
- Machine Learning (Scikit-Learn)
- Pandas / NumPy
- Gradio (UI Interface)
- Windows Event Log Analysis
- Cybersecurity Log Investigation

---

## Machine Learning Model

The project uses a trained classification model that identifies malicious patterns in Windows log entries.

Model artifacts include:

- `windows_threat_detection_model.pkl`
- `label_encoder.pkl`

These models are trained on structured log datasets to classify events into normal or suspicious categories.

---

## Installation

Clone the repository:


git clone https://github.com/ravimnm/ai_based_log_investigation.git

cd ai_based_log_investigation


Install dependencies:


pip install -r requirements.txt


---

## Run the Application

Start the investigation interface:


python app.py


The system will launch a **Gradio interface** where you can upload log files for analysis.

---

## Example Workflow

1. Upload Windows log dataset
2. System processes log entries
3. Machine learning model analyzes patterns
4. Suspicious events are flagged
5. Analyst investigates flagged entries

---

## Use Cases

- SOC threat investigation
- Automated log analysis
- Malware detection research
- Digital forensic analysis
- Security monitoring systems

---

## Future Improvements

- Real-time log streaming analysis
- Integration with SIEM platforms
- Deep learning based anomaly detection
- Cloud-based deployment
- Support for Linux and network logs

---

## Author

Ravi Sankar Manem  
Cybersecurity & Backend Development Enthusiast

GitHub:  
https://github.com/ravimnm

LinkedIn:  
https://linkedin.com/in/ravi-sankar-manem

---

## License

This project is intended for research and educational purposes.
