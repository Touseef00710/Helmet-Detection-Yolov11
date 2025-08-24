🪖 Helmet Detection System using YOLOv11






Overview

AI-powered helmet detection system using YOLOv11 for real-time rider safety monitoring.
Supports inference on images, videos, and live streams, with evaluation metrics including Precision, Recall, F1-score, and mAP.

Features

Train a custom YOLOv11 model on helmet/no-helmet datasets.

Evaluate performance with confusion matrix and per-class metrics.

Run inference on images, videos, or webcam streams.

Tkinter desktop app for easy local deployment.

Save annotated predictions for analysis.

Installation
git clone <your-repo-url>
cd helmet-detection
pip install -r requirements.txt


Requirements: ultralytics, opencv-python, Pillow, tkinter, seaborn, matplotlib, roboflow.

Usage
1️⃣ Colab Training & Evaluation

Open the Colab notebook.

Train the YOLOv11 model on the helmet dataset.

Run evaluation to view metrics and confusion matrix.

2️⃣ Local Tkinter App
python helmet_app.py


Load your trained model (best.pt).

Run inference on images, videos, or webcam.

Evaluate model and view metrics directly in the app.

Dataset

Prepared via Roboflow.

Classes: helmet and no-helmet.

Results

High accuracy with mAP > 0.85.

Confusion matrix highlights class-specific errors.

Annotated predictions saved in outputs/ folder.
