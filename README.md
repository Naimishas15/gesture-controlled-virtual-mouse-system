🖐️ Gesture-Controlled Virtual Mouse System
📌 Overview

A real-time computer vision system that enables users to control mouse movements and perform click actions using hand gestures, eliminating the need for traditional input devices.

❗ Problem

Traditional input devices like a mouse or trackpad limit interaction in touchless environments and accessibility scenarios. There is a need for intuitive, gesture-based control systems that allow seamless human-computer interaction.

💡 Solution

Developed a gesture-controlled virtual mouse using computer vision and hand tracking techniques. The system detects hand landmarks via webcam input and maps finger movements to cursor control and click actions in real time.

🏗️ System Architecture
Input Layer: Webcam video stream
Processing Layer:
Hand detection and tracking using MediaPipe
Landmark extraction and gesture recognition
Control Layer:
Coordinate mapping from camera space to screen space
Cursor smoothing for stable movement
Output Layer:
Mouse movement and click actions using system-level control
⚙️ Tech Stack
Python
OpenCV
MediaPipe
Autopy
NumPy
🔥 Key Features
Real-time hand tracking and gesture detection
Cursor movement using index finger
Click action using pinch gesture (index + middle finger)
Smooth cursor control using interpolation and motion smoothing
Frame rate optimization for responsive interaction
📊 Impact
Demonstrates real-time computer vision system design
Enables touchless interaction with computing systems
Showcases integration of AI perception with system control
Can be extended for accessibility tools, AR/VR interfaces, and smart environments
🚀 How to Run
git clone https://github.com/Naimishas15/gesture-controlled-virtual-mouse-system
cd gesture-controlled-virtual-mouse-system

# Create virtual environment (recommended)
py -3.11 -m venv .venv
.\.venv\Scripts\Activate

# Install dependencies
pip install -r requirements.txt

# Run the project
python VirtualMouse.py


📈 Future Improvements
Multi-hand gesture support
Gesture customization
Integration with AR/VR interfaces
Improved gesture recognition accuracy
Cross-platform optimization