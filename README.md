# 🎓 Face Recognition Attendance System

A smart attendance system using **Python**, **OpenCV**, **YOLOv8**, **Tkinter GUI**, and **face_recognition**. This project automates the attendance process by recognizing registered student faces in real-time and storing attendance logs in `.csv` files.

## 🔧 Features

- 📸 **Live Face Recognition** using YOLOv8 and `face_recognition`
- 🧑‍💼 **Student Registration & Management** (Add, Re-register, Delete)
- ✅ **Real-Time Attendance Marking**
- 📁 **Attendance Log Viewer**
- 💾 Saves data securely in `.pkl` and `.csv` formats
- 🖼️ GUI made with **Tkinter** for user-friendly interaction

## 🖥️ Tech Stack

- **Python**
- **OpenCV**
- **face_recognition**
- **Tkinter**
- **YOLOv8 (via Ultralytics)**
- **PIL**
- **pickle & CSV**

## 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/Sharadkalathiya/face-recognition-attendance-system.git
   cd face-recognition-attendance-system

2. **Install the dependencies**
pip install -r requirements.txt
pip install opencv-python face_recognition pillow ultralytics
   
3. **Run the application**
   python app.py

## 📂 Directory Structure
face-recognition-attendance-system/
│
├── students/                 # Folder for saved student images
├── attendance_*.csv          # Generated attendance files
├── student_encodings.pkl     # Serialized student face encodings
├── app.py                    # Main application script
└── README.md

## ✨ Future Improvements
Email or SMS notification for attendance
Admin login functionality
Cloud-based data storage
Mobile version using Kivy or Flutter

## 📸 Screenshots
![Screenshot 2025-04-14 081457](https://github.com/user-attachments/assets/7d293c2b-966e-491d-a93b-a110966b3097)
![Screenshot 2025-04-14 081509](https://github.com/user-attachments/assets/42f06b49-9db2-47de-9abc-d99ed8fd234c)
![Screenshot 2025-04-14 081526](https://github.com/user-attachments/assets/5ff7c3e5-841d-437e-998c-af991436baf8)
![Screenshot 2025-04-14 081539](https://github.com/user-attachments/assets/86fd6220-3c95-428e-881c-c53b6a83b3de)



