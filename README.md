📸 Contactless Attendance System using Face Recognition

A smart and automated attendance marking system that detects and identifies faces in real-time using a webcam or uploaded images. No manual input required — Zero touch | Fast | Secure.

🚀 Features

🔍 Real-time face detection & recognition

📅 Automatic attendance marking

📊 Attendance logs stored securely (CSV/Database)

🧾 Admin dashboard for users & logs

🖼️ Face registration & dataset creation

🧠 Powered by OpenCV + Machine Learning

💻 Fully contactless — ideal for schools, colleges, offices

🧠 Tech Stack
Component	Technology Used
Language	Python
Face Recognition	OpenCV, Dlib/Face_recognition
UI (Optional)	Flask / Streamlit
Database	CSV / SQLite / Firebase (customizable)
📁 Project Structure
📦 Contactless-Attendance-System
├── 📁 dataset/                # Stored registered face images
├── 📁 models/                 # Encoded face model files
├── 📁 attendance/             # Attendance logs
├── main.py                    # Start attendance system
├── register_face.py           # Add/register new users
├── train_model.py             # Train face recognition model
├── requirements.txt           # Dependencies
└── README.md                  # Documentation file

⚙️ Installation & Setup
# Clone this repo
git clone https://github.com/your-username/contactless-attendance.git
cd contactless-attendance

# Install dependencies
pip install -r requirements.txt

# Register a new face
python register_face.py

# Train the model
python train_model.py

# Run attendance system
python main.py

📊 Output

✔ Detects faces in real-time
✔ Matches with registered students/employees
✔ Automatically logs attendance to .csv like:

Name	Time	Status
Harshith	09:15 AM	Present
🔐 Security & Accuracy

Face encoding stored securely

Can be enhanced with liveness detection

Supports mask-based detection (optional add-on)

High accuracy model training improves overtime

🛠 Future Enhancements

Cloud-connected live dashboard

OTP-verified face enrollment

Multi-camera support

Mobile app integration

🤝 Contributing

Pull requests are welcome!
If you'd like to improve features or UI, feel free to fork & submit PR 🎉
