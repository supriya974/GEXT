🖐️ GEXT – Gesture Recognizer
📘 Overview

GEXT (Gesture Recognizer) is a browser-based hand gesture recognition project.
It uses a machine learning model to detect and recognize user gestures through a webcam in real-time.
The project provides an interactive interface built with HTML, CSS, and JavaScript.

🚀 Features

Real-time gesture detection using webcam.

Interactive and user-friendly UI.

Powered by pre-trained .task models for accurate gesture classification.

Lightweight and runs directly in a browser — no installation required.

Easily extendable for custom gesture datasets.

🧩 Project Structure
GEXT-main/
│
├── index.html             # Main web page
├── style.css              # Styling for the UI
├── script.js              # Core logic for gesture detection
├── model/                 # Contains gesture recognition models
│   ├── gesture_recognizer1.task
│   └── gesture_recognizer2.task
└── README.md              # Project documentation

⚙️ Installation & Setup
Option 1: Run Locally

Clone the repository:

git clone https://github.com/<supriya974>/GEXT.git
cd GEXT


Open the project:
Just open index.html in your browser — no server required!

Allow camera access when prompted.

Option 2: Host on Live Server

If you’re using VS Code, install the Live Server extension.

Right-click on index.html → "Open with Live Server".

🎥 How It Works

The browser accesses your webcam stream.

The pre-trained .task model processes the video frames.

Recognized gestures are displayed on-screen in real time.

🧠 Technologies Used

HTML5, CSS3, JavaScript

TensorFlow.js / MediaPipe (for gesture recognition)

Pre-trained Gesture Models (.task files)

📂 Model Files

The models inside /model/ are responsible for gesture recognition.
They can be replaced or retrained with new gesture sets if desired.

💡 Future Enhancements

Add support for custom gesture training.

Include sound feedback for each gesture.

Build a React or Flask backend version for logging data.

👩‍💻 Author

Supriya Das
📧 Email: supriyadas06102002@gmail.com
🌐 GitHub: https://github.com/supriya974

📜 License

This project is licensed under the MIT License — you are free to use, modify, and distribute it with attribution.
