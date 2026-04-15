# 🚑 Accident Detection System

## 📌 Description
This project detects accidents using ESP8266 and sends alerts via SMS and a Flask server.

## 🔧 Components Used
- ESP8266
- GPS Module (Neo-6M)
- GSM Module (SIM800/900)
- MPU6050 (Accelerometer + Gyroscope)
- LCD Display (I2C)

## 🌐 Features
- Automatic accident detection
- Real-time GPS tracking
- SMS alert to contacts
- Nearest hospital detection using Flask API
- Works in both Online and Offline mode

## 🚀 How to Run Server

1. Go to Server folder:
   cd Server

2. Install requirements:
   pip install -r ../requirements.txt

3. Run server:
   python app.py

## 📡 ESP Setup
- Open `accident_system.ino` in Arduino IDE
- Select ESP8266 board
- Upload the code

## 🔐 Security
API keys are stored in `.env` file and not uploaded to GitHub.

## 👨‍💻 Author

Gokul.VG and Divya Nandhini.V