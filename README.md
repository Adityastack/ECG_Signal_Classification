# ECG Signal Classification using Machine Learning

## 📌 Project Overview

This project presents an automated ECG (Electrocardiogram) signal classification system using Machine Learning and Deep Learning techniques. The model is trained on the MIT-BIH Arrhythmia Dataset to classify ECG heartbeat signals and assist in the early detection of cardiac abnormalities.

The complete workflow includes data preprocessing, feature scaling, neural network model training, performance evaluation, and visualization of training metrics.

---

## 🚀 Features

- ECG signal preprocessing
- Feature scaling using StandardScaler
- Label encoding for target classes
- Deep Neural Network built with TensorFlow/Keras
- Model evaluation using Accuracy, Precision, Recall and F1-Score
- Confusion Matrix generation
- Training & Validation Accuracy/Loss visualization
- Model saving for future inference

---

## 📂 Dataset

**Dataset Used:** MIT-BIH Arrhythmia Dataset

Files:
- `mitbih_train.csv`
- `mitbih_test.csv`

Source:
https://www.kaggle.com/datasets/shayanfazeli/heartbeat

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

## 📁 Project Structure

```
ECG-Signal-Classification/
│
├── ECG_Signal_Classification.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## ⚙️ Workflow

1. Load ECG Dataset
2. Preprocess the Data
3. Scale Features
4. Encode Labels
5. Build Deep Neural Network
6. Train the Model
7. Evaluate Performance
8. Plot Training Curves
9. Save the Trained Model

---

## 📊 Model Evaluation

The trained model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Training and validation curves are also plotted to monitor learning performance.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/ECG-Signal-Classification.git
```

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Download the MIT-BIH dataset and place:

```
mitbih_train.csv
mitbih_test.csv
```

inside the working directory.

4. Run all notebook cells.

---

## 🎯 Applications

- Automated Arrhythmia Detection
- Clinical Decision Support
- Healthcare AI
- Biomedical Signal Processing
- Medical Diagnosis Assistance

---

## 🔮 Future Scope

- CNN-based ECG Classification
- LSTM-based Sequential Learning
- Real-Time ECG Monitoring
- Deployment using Flask/Streamlit
- Integration with IoT Healthcare Devices

---

## 👨‍💻 Authors

**Aditya Pratap Singh Bhadoriya**

Bachelor of Technology  
Electronics & Telecommunication Engineering

---

## 📜 License

This project is developed for educational and research purposes.
