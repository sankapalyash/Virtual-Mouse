🖐️ Virtual Mouse using Hand Gesture Recognition

A computer vision-based virtual mouse that allows users to control the cursor using hand gestures in real time. This system eliminates the need for a physical mouse and enables touchless interaction using a webcam.

🚀 Features
Real-time hand tracking
Cursor control using index finger
Gesture-based clicking and scrolling
Smooth movement with reduced jitter
Works with a standard webcam
🛠️ Tech Stack
Python
OpenCV
MediaPipe
PyAutoGUI
⚙️ How It Works
Captures live video using webcam
Detects hand and extracts landmarks
Tracks finger positions
Maps gestures to mouse actions:
Move → Index finger movement
Click → Thumb + index finger
Scroll → Two-finger gesture
📦 Installation
git clone https://github.com/your-username/virtual-mouse.git
cd virtual-mouse
pip install -r requirements.txt
▶️ Usage
python main.py

Make sure your webcam is enabled.

📌 Requirements
Python 3.x
Webcam
Required libraries (see requirements.txt)
⚠️ Limitations
Performance depends on lighting conditions
Background noise may affect accuracy
Slight delay (latency) possible
Can cause hand fatigue over long use
📈 Future Improvements
Gesture customization
Multi-hand support
AI-based gesture classification
Performance optimization
🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss.
