Helmet Detection using YOLOv11
https://img.shields.io/badge/Python-3.8%252B-blue
https://img.shields.io/badge/Ultralytics-YOLOv11-red
https://img.shields.io/badge/Streamlit-Dashboard-green
https://img.shields.io/badge/License-MIT-yellow

A complete computer vision pipeline for real-time helmet detection using YOLOv11, featuring model training, evaluation, and an interactive web dashboard with webcam support.

📋 Overview
This project implements a robust helmet detection system that:

Trains a YOLOv11 model on 13 helmet classes

Achieves 89% mAP@0.5 detection accuracy

Provides real-time inference through webcam or image upload

Features an interactive Streamlit dashboard for visualization

Deploys seamlessly on Google Colab with ngrok tunneling

🚀 Features
High Accuracy: 89% mAP@0.5 with 92.5% precision

Real-time Detection: Webcam support with live inference

Multi-Input Support: Image upload and camera capture

Interactive Dashboard: Streamlit-based UI with adjustable confidence thresholds

Comprehensive Analytics: Training metrics, confusion matrix, and performance statistics

Easy Deployment: One-click Colab setup with ngrok integration

🛠️ Installation
bash
# Clone the repository
git clone https://github.com/touseefahmed/helmet-detection-yolov11.git
cd helmet-detection-yolov11

# Install dependencies
pip install ultralytics roboflow streamlit pyngrok pillow opencv-python matplotlib seaborn pandas
📊 Dataset
The model is trained on the Helmet Detector dataset from Roboflow:

13 helmet classes

1,702 training images

572 validation images

YOLOv11 annotation format

🏗️ Model Architecture
Model: YOLOv11 Nano (2.5M parameters)

Input Resolution: 640×640 pixels

Training Epochs: 50

Optimizer: AdamW (auto-selected)

mAP@0.5: 0.890

Precision: 0.925

Recall: 0.860

🎯 Usage
Google Colab Deployment
Open the notebook in Google Colab

Run all cells sequentially

The Streamlit dashboard will automatically launch

Access via the provided ngrok URL

Local Deployment
bash
# Run the Streamlit dashboard locally
streamlit run helmet_detection_dashboard.py
Using the Dashboard
Image Upload Tab: Upload images for helmet detection

Webcam Tab: Use your camera for real-time detection

Model Info Tab: View training metrics and performance statistics

Adjust Confidence: Use the slider to modify detection sensitivity

📈 Performance
Metric	Value
mAP@0.5	0.890
Precision	0.925
Recall	0.860
F1-Score	0.891
Inference Speed	45-65ms (Tesla T4)
🖼️ Sample Results
https://via.placeholder.com/600x400/FFFFFF/000000?text=Helmet+Detection+Example
Example of helmet detection on construction site imagery

https://via.placeholder.com/600x400/FFFFFF/000000?text=Streamlit+Dashboard
Interactive Streamlit dashboard with real-time analytics

🏆 Applications
Construction Safety: Monitor helmet compliance on sites

Sports Safety: Ensure proper helmet usage in cycling, skiing, etc.

Industrial Monitoring: Warehouse and factory safety compliance

Educational Tools: Safety training and awareness programs

👨‍💻 Author
Touseef Ahmed

GitHub: @touseefahmed

Email: touseef.ahmed@example.com

LinkedIn: Touseef Ahmed

Roboflow for the helmet detection dataset

Streamlit for the dashboard framework

Ngrok for tunneling solution
