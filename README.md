# Intelligent Network Intrusion Detection System Using Machine Learning

An intelligent machine learning system for detecting and classifying network intrusion attacks using the **Random Forest Classifier** and the **UNSW-NB15** dataset.

---

## Overview

This project presents a Network Intrusion Detection System (NIDS) that analyzes network traffic and automatically classifies different types of cyber attacks using Machine Learning.

The model was trained on the **UNSW-NB15** dataset and learns patterns from network traffic features to distinguish between normal activities and malicious attacks. The project also includes data preprocessing, visualization, model training, and performance evaluation.

---

## Features

- Network traffic analysis
- Data preprocessing and cleaning
- Categorical feature encoding
- Feature scaling
- Machine Learning classification using Random Forest
- Model performance evaluation
- Confusion Matrix visualization
- Feature Importance analysis
- Attack category prediction

---

## Dataset

**Dataset:** UNSW-NB15

The dataset contains network traffic records with multiple features representing communication between hosts. Each record belongs to either normal traffic or a specific attack category.

Example features include:

- Duration (`dur`)
- Protocol (`proto`)
- Service (`service`)
- Connection state (`state`)
- Source packets (`spkts`)
- Destination packets (`dpkts`)
- Source bytes (`sbytes`)
- Destination bytes (`dbytes`)
- Transmission rate (`rate`)
- ...and many more.

**Target Variable**

- `attack_cat`

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

---

## Machine Learning Workflow

1. Import required libraries
2. Load the UNSW-NB15 dataset
3. Data exploration
4. Data cleaning
5. Feature encoding
6. Feature scaling
7. Train-test split
8. Train the Random Forest model
9. Evaluate model performance
10. Predict attack categories
11. Visualize results

---

## Machine Learning Model

**Algorithm**

- Random Forest Classifier

The Random Forest algorithm was selected because of its high accuracy, robustness, and ability to handle large datasets with many features.

---

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Project Structure

```
project/
│
├── projectCyberDetection.ipynb
├── UNSW_NB15.csv
├── README.md
└── images/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/network-intrusion-detection.git
```

Install the required packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## Usage

Open the notebook:

```bash
jupyter notebook projectCyberDetection.ipynb
```

or upload it directly to **Google Colab** and run the cells sequentially.

---

## Results

The trained model successfully classifies different categories of network attacks using network traffic features and achieves strong classification performance after preprocessing and training.

---

## Future Improvements

- Deploy the model as a web application using Flask or Streamlit.
- Add real-time network traffic monitoring.
- Compare additional Machine Learning algorithms.
- Experiment with Deep Learning approaches.
- Improve model performance through hyperparameter tuning.

---

## Author

**Anas Mohammed Abdul Jalil Saeed**

Artificial Intelligence Student  
University of Taiz

---

## License

This project is intended for educational and research purposes.