# Alphabet-Detection
Alphabet detection identifies and classifies hand gestures representing letters, enabling recognition of sign language alphabets. Using computer vision and deep learning models like YOLO and LSTM, it translates visual inputs into corresponding alphabetic characters for accessibility and communication.

# ✨ Features
🔍 Real-time alphabet gesture detection
⚡ Fast & lightweight YOLOv8 model
🎥 Supports images, videos, and webcam input
🛠 Easy to run and customize
📈 Pre-trained on a custom sign language alphabet dataset

2.Install dependencies
pip install -r requirements.txt

3.Ensure model weights are available
Place your trained weights (best.pt) in the project folder.

🚀 Usage
Run Detection
python try.py

Evaluate Model
python evaluate_yolo.py

📂 Project Structure
alphabetsDetection/
│-- try.py                # Main detection script
│-- evaluate_yolo.py      # Model evaluation
│-- requirements.txt      # Python dependencies
│-- yolov8n.pt             # YOLOv8 base model
│-- best.pt                # Trained weights for alphabet detection
│-- runs/                  # Training results and logs
📊 Model Details
Base Model: YOLOv8n

Framework: Python, PyTorch

Training Data: Custom alphabet gesture dataset

Output: Predicted alphabet with bounding box & confidence score
