Face Recognition Attendance System
📌 Overview

The Face Recognition Attendance System is a computer vision-based application that automates attendance marking using facial recognition technology. The system detects and recognizes faces in real time through a webcam and records attendance automatically, reducing manual effort and improving reliability.

This project demonstrates the practical implementation of face detection and recognition techniques for real-world attendance management use cases.

🚀 Features

Real-time face detection and recognition

Automated attendance recording

Reduced manual errors and proxy attendance

Lightweight and easy to use

Digital attendance storage

🛠️ Tech Stack

Language: Python

Libraries: OpenCV, Face Recognition, NumPy

Concepts: Computer Vision, Image Processing, Face Encoding

Storage: CSV File System

📂 Project Structure
Face-recognition-Attendance/
│
├── images/                # Registered user images
├── attendance.csv         # Attendance records
├── main.py                # Main application file
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Mantavyakumar/Face-recognition-Attendance.git

2️⃣ Move to Project Directory
cd Face-recognition-Attendance

3️⃣ Install Dependencies
pip install opencv-python face-recognition numpy

4️⃣ Run the Application
python main.py

🔄 How It Works

The system loads images of registered users.

Face encodings are generated and stored.

Webcam captures live video input.

Faces are detected and matched with stored data.

Attendance is recorded automatically in the attendance file.

📈 Future Improvements

Database integration (MySQL/MongoDB)

Web or GUI interface

User registration module

Cloud deployment support

Attendance analytics dashboard

👨‍💻 Author

Mantavya Kumar
