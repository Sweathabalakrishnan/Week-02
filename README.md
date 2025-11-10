

# Week-02

# 🧠 SmartWaste: AI Powered Waste Classification System

♻️ An Intelligent Waste Classification Software using CNN and Voice Feedback

---

🚀 Overview

SmartWaste is an AI-based waste classification software that automatically identifies waste images as Organic or Recyclable using a Convolutional Neural Network (CNN) built with MobileNetV2.
The system integrates a voice assistant (pyttsx3) for announcing results and provides a simple dashboard to visualize predictions and accuracy.

This project supports sustainable waste management and encourages eco-friendly automation using AI technology.

---

🧩 Features

✅ Image classification using a pre-trained MobileNetV2 CNN
✅ Voice feedback announcing classification results
✅ Dashboard to display accuracy, confusion matrix, and predictions
✅ Option to retrain the model with custom datasets
✅ Lightweight and runs fully offline

---

🧠 Technologies Used

* Python 3.10+
* TensorFlow / Keras – Model training and prediction
* Matplotlib / Seaborn – Data visualization
* Scikit-learn – Model evaluation
* Pyttsx3 – Voice feedback
* Tkinter / Streamlit (optional) – Dashboard display

---

📂 Project Structure

SmartWaste/
│
├── dataset/
│   ├── TRAIN/
│   │   ├── Organic/
│   │   └── Recyclable/
│   ├── TEST/
│       ├── Organic/
│       └── Recyclable/
│
├── smartwaste_model.py        → CNN model training script
├── smartwaste_predict.py      → Prediction + Voice output
├── dashboard.py               → Dashboard visualization
├── requirements.txt           → Required dependencies
└── README.md                  → Project documentation

---

⚙️ Installation

1. Clone the repository
   git clone [https://github.com/Sweathabalakrishnan/SmartWaste.git](https://github.com/Sweathabalakrishnan/SmartWaste.git)
   cd SmartWaste

2. Install dependencies
   pip install -r requirements.txt
   (Make sure TensorFlow, Keras, and pyttsx3 are installed)

3. Run the model training
   python smartwaste_model.py

4. Run the prediction with voice feedback
   python smartwaste_predict.py

5. Launch dashboard (optional)
   python dashboard.py

---

🗣️ Voice Feedback Example

When an image is classified, the system speaks:
“The given waste item is Organic.”
or
“The given waste item is Recyclable.”

---

📊 Results

Model Accuracy: ~92%
Model Used: MobileNetV2 (Transfer Learning)
Dataset: Waste Classification Dataset (Kaggle / Custom)

---

🌍 Future Enhancements

* Add real-time image capture from webcam
* Deploy as a web app using Streamlit or Flask
* Integrate with IoT bins for automatic waste segregation
* Add multilingual voice support

---

👩‍💻 Author

Sweatha Balakrishnan
B.Tech in Artificial Intelligence and Data Science
Passionate about AI, Data Analytics, and Sustainable Technology

GitHub: [https://github.com/Sweathabalakrishnan](https://github.com/Sweathabalakrishnan)

---


