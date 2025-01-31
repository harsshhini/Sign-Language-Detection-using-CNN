# Sign-Language-Detection-using-CNN


## 📌 Overview
This project is a deep learning-based Sign Language to Text conversion system. It utilizes a Convolutional Neural Network (CNN) model to recognize sign language gestures and convert them into text. This system aims to aid communication for the hearing and speech impaired.

## ✨ Features
- Real-time sign language recognition
- Supports multiple hand gestures
- Converts recognized signs into text
- User-friendly interface
- High accuracy using a CNN model

## 🛠️ Technologies Used
- Python
- OpenCV
- TensorFlow/Keras
- NumPy & Pandas
- Matplotlib

## 📂 Project Structure
```
📁 Sign-Language-Detection-sing-CNN
│── 📜 app.py   
│── 📜 collectdata.py      
│── 📜 data.py     
│── 📜 function.py      
│── 📜 trainmodel.py      
│── 📜 README.md           # Project documentation
```

## 🚀 Installation & Usage

### **Prerequisites**
Ensure you have Python installed (preferably Python 3.8 or higher). You can download it from [Python Official Website](https://www.python.org/downloads/).

### **1️⃣ Clone the Repository**
Open a terminal and run:
```bash
git clone https://github.com/yourusername/SignLanguageToText.git
cd SignLanguageToText
```

### **2️⃣ Create a Virtual Environment (Optional but Recommended)**
```bash
python -m venv env  # Create virtual environment
source env/bin/activate  # Activate on macOS/Linux
env\Scripts\activate  # Activate on Windows
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4️⃣ Train the Model (If Needed)**
If you need to train the model, run:
```bash
python train_model.py
```

### **5️⃣ Run the Sign Language Recognition**
```bash
python sign_language.py
```
This will start the real-time recognition system using your webcam.

### **6️⃣ Deactivate Virtual Environment (If Used)**
```bash
deactivate
```

### Real-time Recognition
![Real-time Prediction](ProjectDemoImages/)
