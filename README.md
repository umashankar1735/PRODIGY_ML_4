# PRODIGY_ML_4
# Hand Gesture Recognition using CNN ✋🤖

## Overview
This project implements a **Hand Gesture Recognition** system using a **Convolutional Neural Network (CNN)** trained on the **LeapGestRecog** dataset. The model can classify different hand gestures, making it useful for applications like human-computer interaction, gaming, and assistive technologies.

## Features
✅ **Preprocessing**: Image resizing, grayscale conversion, and normalization.  
✅ **Model Architecture**: CNN-based deep learning model for gesture recognition.  
✅ **Real-time Prediction**: Uses OpenCV for live gesture recognition.  
✅ **Performance Optimization**: Data augmentation and hyperparameter tuning.  

## Dataset
**LeapGestRecog Dataset**: A collection of grayscale hand gesture images, categorized into multiple gesture classes. Ensure that the dataset is downloaded and placed in the appropriate directory.

Dataset Path:  
`C:\Users\navan\Downloads\HAND GESTURE\leapGestRecog`

## Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/hand-gesture-recognition.git
cd hand-gesture-recognition
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run the Training Script
```bash
python train_model.py
```
### 4️⃣ Test the Model
```bash
python test_model.py
```
### 5️⃣ Real-time Gesture Detection
```bash
python real_time_gesture.py
```

## Model Training
- The CNN model is trained using **TensorFlow/Keras**.
- Optimized using **Adam optimizer**.
- Evaluation using **accuracy, precision, recall, and confusion matrix**.

## Results & Insights
📌 **Gesture recognition accuracy** achieved: ~XX% (based on testing).  
📌 **Key learning**: Gesture classification requires careful feature extraction and lighting conditions impact recognition.  
📌 **Future improvements**: Exploring transformer-based vision models for better accuracy.  

## Folder Structure
```
├── leapGestRecog/          # Dataset Folder
├── models/                 # Trained Model Files
├── scripts/
│   ├── train_model.py      # Model Training Script
│   ├── test_model.py       # Model Testing Script
│   ├── real_time_gesture.py # Live Gesture Recognition
├── README.md               # Project Documentation
└── requirements.txt        # Dependencies
```

## Contributors
- **[Your Name]** – AI/ML Developer 🤖

## License
📜 This project is licensed under the **MIT License**.

---

💡 **Let’s Make AI More Interactive!** If you find this useful, feel free to ⭐ the repo and contribute! 🚀
