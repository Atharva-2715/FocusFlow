💻 FocusFlow
FocusFlow is a real-time attention monitoring tool designed for virtual meetings and online classrooms. It detects whether a participant is present, focused, or multitasking — and alerts the host if attention drops.

Built during a hackathon at VIT Chennai by Team Error 404.

🚀 Features
✅ Real-time attention tracking via webcam

✅ Alerts host if participant is absent, distracted, or multitasking

✅ Simple and clean web interface

✅ Seamless integration with video calls and virtual sessions

🛠 Tech Stack
Backend & Logic:

Python

dlib (facial landmark detection)

pygetwindow (detect active application)

numpy (numerical computations)

Frontend:

HTML

CSS

JavaScript

🧪 Installation
bash
Copy
Edit
git clone https://github.com/your-username/focusflow.git
cd focusflow
pip install -r requirements.txt
Make sure you have a webcam connected and Python 3.7+ installed.

⚙️ How It Works
The Python script uses dlib to track facial landmarks and detect eye aspect ratio (EAR).

pygetwindow checks if Zoom, Meet, or any specified app is the active window.

If the user is not attentive or has switched windows, a real-time alert is sent to the host.

The web interface displays current attention status for quick monitoring.
