
![DEEPFAKE](https://github.com/user-attachments/assets/6952f206-11e4-4ed3-ad73-a2662eb5fd15)


# AI Against AI: A Deep Learning Approach to Detecting Deepfakes

This project is a proof-of-concept web-based tool designed to detect deepfake videos using AI-powered models. It uses computer vision and deep learning techniques to analyze video frames and identify manipulated or synthetic content.

---

## 🔍 Objective

As deepfakes become more realistic and widespread, there's a pressing need to detect them automatically. This project aims to:

- Detect facial manipulation in videos using deep learning.
- Offer a simple web interface for uploading and analyzing videos.
- Provide a visual indication of whether a video is authentic or likely a deepfake.

---

## 🧪 Features

- Upload and process videos via a browser
- Frame-by-frame facial region analysis
- Deep learning classification using CNN/LSTM or pretrained models
- Result displayed as a confidence score or binary prediction
- Modular structure for future model upgrades

---

## 🛠️ Technologies Used

- **Python 3.10+**
- **TensorFlow / PyTorch**
- **OpenCV**
- **Flask** (for the web interface)
- **NumPy, Matplotlib**
- **Pretrained model** (e.g., XceptionNet or custom CNN)

---

## 🚀 Setup Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/MayankNarain/deepfake-detector.git
   cd deepfake-detector

2. Create a virtual Enviroment and activate it:
   ```bash
   python -m venv venv
   venv\Scripts\activate   # Windows
   source venv/bin/activate  # Mac/Linux

3. Install Dependencies:
   ```bash
   pip install -r requirements.txt

4. Run the Web Page:
   ```bash
   python app.py

5.Go to browser and visit
   https://127.0.1:500/

---

📌 Limitations
This is a prototype, not a production system.
Performance may vary depending on the dataset and hardware.
Model accuracy can be improved with more training data and fine-tuning.

🧠 Acknowledgements
FaceForensics++ Dataset

Deepware Scanner inspiration

XceptionNet architecture

OpenCV + Flask Community

You can copy this into your `README.md` and update your repo URL, LinkedIn, or model info as needed.


   
   
   
   
   
