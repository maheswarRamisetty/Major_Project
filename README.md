Traffic Analysis System
A real-time traffic monitoring and analysis system that detects lanes and vehicles from CCTV video footage using deep learning models (YOLO, lane detection models like YOLOP), and provides per-lane vehicle counts, traffic intensity, and a dashboard for visualization.

📌 Features
Vehicle detection using YOLOv8

Real-time and historical video input support

Unique ID assignment to each vehicle to prevent double counting

Interactive traffic dashboard for live traffic metrics

Multi-camera video support for full road segment analysis



🛠️ Installation
Prerequisites
Python 3.8+

pip

Git

GPU recommended (NVIDIA CUDA)

Clone the Repository



git clone https://github.com/yourusername/traffic-analysis-system.git
cd traffic-analysis-system
Create a Virtual Environment

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies


pip install -r requirements.txt



Run -  main.ipnyb (all cells)




