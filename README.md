# Plant-Disease-Detection

# 🌿 Plant Disease Detection using Machine Learning

This project is a **Plant Disease Detection System** built using **Machine Learning and Computer Vision**.  
It identifies plant diseases from leaf images and suggests possible treatments, helping farmers and researchers to ensure healthy crop yield.

---

## 🚀 Features

- 🌱 Detects multiple plant diseases from leaf images  
- 🤖 Trained with **deep learning (CNN)** models such as TensorFlow/Keras  
- 📸 Allows users to **upload images** of leaves  
- 💊 Provides disease name and **recommended cure or pesticide**  
- 🌐 Integrated with a **Flask-based web interface** for easy use  
- 🧾 Displays confidence score for predictions  

---

## 🏗️ Project Structure

Plant-Disease-Detection/
│
├── static/ # CSS, JS, and images for the web app
├── templates/ # HTML templates (Flask)
├── model/ # Trained model files (.h5 or .pkl)
├── dataset/ # Training & validation dataset
├── app.py # Flask backend application
├── requirements.txt # Dependencies
└── README.md # Project documentation


---

## ⚙️ Installation Guide
```bash
1️⃣ Clone this repository
git clone https://github.com/yashwanthms25/Plant-Disease-Detection.git
cd Plant-Disease-Detection

2️⃣ Create a virtual environment (recommended)
python -m venv venv
venv\Scripts\activate    # for Windows
# OR
source venv/bin/activate # for Linux/Mac

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the Flask app
python app.py

