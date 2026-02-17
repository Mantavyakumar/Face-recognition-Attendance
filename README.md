Face Recognition Attendance System
📌 Overview

The Face Recognition Attendance System is a computer vision-based application that automates attendance marking using facial recognition technology. The system detects and recognizes registered faces through a camera and automatically records attendance, reducing manual effort and improving accuracy.

This project demonstrates the practical use of face detection and recognition for real-time attendance management.

🚀 Features

Real-time face detection using webcam

Automatic attendance marking

Stores attendance records digitally

Reduces manual errors

Easy to use and scalable

🛠️ Technologies Used

Python

OpenCV

Face Recognition Library

NumPy

CSV/File Handling

📂 Project Structure
Face-recognition-Attendance/
│
├── images/              # Stored face images
├── attendance.csv       # Attendance records
├── main.py              # Main execution file
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/Mantavyakumar/Face-recognition-Attendance.git

2️⃣ Navigate to project folder
cd Face-recognition-Attendance

3️⃣ Install dependencies
pip install opencv-python
pip install face-recognition
pip install numpy

4️⃣ Run the project
python main.py

✅ How It Works

The system loads stored images of registered users.

Faces are encoded and stored.

Webcam captures live video.

Faces are detected and matched with stored data.

Attendance is automatically recorded in the attendance file.

📈 Future Improvements

Database integration

GUI interface

Multiple camera support

Cloud-based attendance storage

👨‍💻 Author

Mantavya Kumar
