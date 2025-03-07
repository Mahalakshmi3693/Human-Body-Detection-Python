# Human Body Detection using Python

## Description
The **Human Body Detection** project is a Python-based application that utilizes computer vision techniques to detect human bodies in images or video streams. This project can be used for various applications, such as security surveillance, pedestrian detection, and AI-powered monitoring systems.

## Features
- Real-time human body detection
- Image and video processing capabilities
- Uses pre-trained deep learning models for accuracy
- Lightweight and easy to integrate into other applications

## Technologies Used
- **Python** – Primary programming language
- **OpenCV** – Library for image and video processing
- **TensorFlow / Keras** – (Optional) For deep learning-based detection
- **YOLO / Haar Cascades** – Pre-trained models for human detection

## Installation & Setup
### **1. Clone the Repository**
```sh
   git clone https://github.com/yourusername/human-body-detection.git
   cd human-body-detection
```

### **2. Create a Virtual Environment (Optional but Recommended)**
```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
```

### **3. Install Dependencies**
```sh
   pip install -r requirements.txt
```

### **4. Run the Application**
```sh
   python main.py
```

## Usage
- The script processes video frames and detects human bodies in real-time.
- If using image detection, modify `main.py` to specify an image file as input.
- Adjust detection model parameters in the script for better accuracy.

## Conclusion
This **Human Body Detection** project demonstrates the use of computer vision techniques to identify human bodies in various environments. It can be further enhanced with deep learning models for improved accuracy and efficiency.
