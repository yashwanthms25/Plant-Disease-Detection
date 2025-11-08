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

```
🧠 Model Details
Algorithm: Convolutional Neural Network (CNN)
Framework: TensorFlow / Keras
Dataset: Publicly available plant disease datasets (PlantVillage, Kaggle, etc.)
Input: Leaf image (.jpg / .png)
Output: Predicted disease name + cure suggestion

💻 Technologies Used

Python 3.9+
Flask (Web framework)
TensorFlow / Keras (Model training)
OpenCV (Image preprocessing)
NumPy, Pandas, Matplotlib
HTML / CSS / JavaScript (Frontend)

📈 Future Improvements
🌍 Deploy model using Streamlit or FastAPI
☁️ Host on AWS / Render / Hugging Face Spaces
📱 Build a mobile app interface
🧾 Add voice-based disease query assistant
