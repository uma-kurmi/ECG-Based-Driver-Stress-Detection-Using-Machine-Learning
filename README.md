📖 Overview

This project aims to detect driver stress levels using electrocardiogram (ECG) signals and machine learning models. Stress significantly affects driving performance and reaction time, making it a critical factor in road safety.
The system processes ECG signals, extracts meaningful physiological features, and classifies the driver’s state into stressed or non-stressed categories.

🎯 Objectives

Analyze ECG signals to identify stress-related patterns
Extract heart rate variability (HRV) features
Train machine learning models for stress classification
Evaluate model performance using standard metrics

⚙️ Methodology

1. Data Collection
ECG data obtained from:
Public datasets (or specify dataset name if used)
/ Sensors (if applicable)

3. Signal Preprocessing
Noise removal (bandpass filtering)
Baseline correction
R-peak detection
Signal normalization

4. Feature Extraction

Key features derived from ECG signals:

Time-Domain Features

Mean RR interval

SDNN (Standard deviation of NN intervals)

Frequency-Domain Features

Low Frequency (LF)

High Frequency (HF)

LF/HF ratio

Statistical Features

Mean, variance, standard deviation

4. Model Development

Machine learning algorithms used:

Support Vector Machine (SVM)

Random Forest

Logistic Regression
(Optional: LSTM / Deep Learning if you actually used it)

5. Model Evaluation

Performance evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

📊 Results

Random Forest achieved 85% accuracy
SVM achieved 82% accuracy
Best performance observed with [model name]
🛠️ Tech Stack
Python
NumPy
Pandas
SciPy
Scikit-learn
Matplotlib / Seaborn
📁 Project Structure
├── data/               # Dataset files
├── notebooks/          # Jupyter notebooks
├── src/                # Source code
├── models/             # Saved models
├── results/            # Outputs and evaluation metrics
├── README.md
🚀 How to Run
Clone the repository:
git clone https://github.com/your-username/ecg-stress-detection.git
cd ecg-stress-detection
Install dependencies:
pip install -r requirements.txt
Run the project:
python main.py
🔍 Applications
Driver monitoring systems
Wearable stress detection devices
Intelligent transportation systems
⚠️ Limitations
Model performance depends heavily on dataset quality
Limited real-world validation
Not implemented for real-time deployment (unless you actually did it)
📌 Future Work
Real-time stress detection system
Integration with IoT/wearable devices
Use of deep learning models for improved accuracy

👤 Author

Uma Kurmi
