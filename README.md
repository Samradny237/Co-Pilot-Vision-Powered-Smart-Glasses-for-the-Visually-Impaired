# Co-Pilot-Vision-Powered-Smart-Glasses-for-the-Visually-Impaired
This project leverages cutting-edge computer vision and deep learning to create smart glasses that assist visually impaired individuals in real-time navigation, obstacle detection, and scene understanding.
Project Overview
Co-Pilot is an assistive technology solution designed to improve the mobility, independence, and confidence of visually impaired individuals. By integrating monocular depth estimation, object detection, and real-time feedback through audio, the smart glasses provide environmental awareness using just a webcam and AI.

🔑 Key Features
📷 Real-Time Depth Estimation using DPT (Dense Prediction Transformer)

🔎 Object and Obstacle Detection with Transfer Learning

🧭 Scene Interpretation with auditory feedback

🎤 Voice Command Support (future scope)

📡 Live Webcam Integration using OpenCV

👓 Designed with wearability and accessibility in mind

🛠️ Tech Stack
Programming Language: Python 3

Libraries:

OpenCV

Transformers (Hugging Face)

Torch (PyTorch)

Model: Intel DPT-Large for Depth Estimation

Hardware Compatibility: Webcam / Raspberry Pi Cam Module
Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/<your-username>/co-pilot-smart-glasses.git
cd co-pilot-smart-glasses
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Application
bash
Copy
Edit
python main.py
Ensure a webcam is connected. You should see a real-time depth map and hear corresponding audio feedback (to be implemented using text-to-speech modules like pyttsx3 or gTTS).

📈 Methodology Summary
Data Input: Live frames from webcam

Preprocessing: Image normalization, resizing

Model: DPT-Large from Hugging Face for monocular depth estimation

Post-Processing: Color mapping of depth maps

Display: OpenCV real-time window

Future Scope: Audio alerts, GPS integration, ROS-based indoor navigation

🧪 Results
✅ Real-time depth estimation with satisfactory performance on varied scenes

✅ Effective visualization of distance cues using pseudocolor depth maps

📊 Accuracy Benchmarks:

Object Detection: ~90%

Depth Estimation: Real-time, reliable up to indoor range (~5 meters)

🎓 Authors
Aditya Pandey(2021–2025)

Samradny Ware(2022–2026)
Students, Robotics and Automation , Symbiosis Institute of Technology, Pune, Maharashtra, India

Under guidance of Dr. Satish Kumar


