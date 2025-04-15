# FocusFlow FocusFlow is a tool designed to enhance productivity and engagement during virtual meetings and online classes. It monitors the attention of participants by detecting whether they are multitasking, distracted, or absent, and sends real-time alerts to the host if attention drops.

Features
Real-time attention detection using webcam feed

Automatic alert system when a participant is not paying attention or is absent

Simple, user-friendly web interface for both participants and hosts

Integration with facial landmark detection for precise attention tracking

Tech Stack
Python: Core logic and attention detection algorithm

pygetwindow: For window management and determining active applications

dlib: For facial landmark detection and eye aspect ratio (EAR) calculation

numpy: For numerical operations and calculations in the algorithm

HTML/CSS/JS: Front-end for the user interface

Installation
To get started, clone the repository and install the necessary dependencies:

bash
Copy
Edit
git clone https://github.com/your-username/focusflow.git
cd focusflow
pip install -r requirements.txt
How It Works
The system uses webcam feed to analyze the participant's eye movements and determine if they are paying attention.

If the attention drops (e.g., the user is looking away or not present), the system triggers an alert to the host.

The host is notified in real-time through an alert message, prompting them to take action.

Usage
Run the Python script to start the attention detection.

Open the web interface to monitor the session.

The system will continuously track the participants' attention during the session.

Contributing
Feel free to fork the repository, create a branch, and submit pull requests. If you have any questions or suggestions, don’t hesitate to open an issue!

