# Hi, I'm Zahan

**Embedded Systems, Computer Vision & Local AI**

---

### About Me
- Background in embedded systems and computer vision
- Currently building an AI-powered security system as my final year project
- Exploring how small language models run on everyday hardware (laptop CPU, edge devices)
- Also do freelance work in logo design and website customization

---

### Technical Skills
**Languages:** Python, C/C++, JavaScript, MATLAB
**Embedded:** Arduino, Raspberry Pi 5, PIC18F452, ESP32, NI myRIO/LabVIEW
**AI/ML:** YOLOv8, U-Net, Transfer Learning, OpenCV
**Local LLMs:** OpenVINO GenAI, Ollama, Qwen 2.5, Gemma 3, FP16/INT8/INT4 quantization
**Web/Backend:** Flask, SQLite, Bootstrap 5, Gmail API
**Tools:** Git

---

### Featured Projects

**Running Qwen 2.5 (1.5B, FP16) on a Laptop CPU**
Ran a small language model fully on CPU with no GPU, using OpenVINO GenAI.
- Measured speed: about 7.9 tokens/sec with 834 ms time to first token (FP16)
- Tuned generation quality with temperature, top_p, top_k and prompt window settings
- Also tested INT8 and INT4 versions, and Gemma 3 1B for comparison
`OpenVINO` `Qwen 2.5` `Quantization` `Python`

**Local AI Email Classifier** (in progress)
Reads my Gmail and marks each email as IMPORTANT or NOT IMPORTANT, with a short reason. Everything runs locally.
- Connects to Gmail with read-only OAuth, extracts sender, subject, date and decoded body
- Flask API (`/analyze`) checks for urgent keywords first, and only calls the Qwen model when no keyword matches
`Gmail API` `Flask` `OpenVINO` `Qwen 2.5`

**AI-Powered Smart Security & Home Automation** (Final Year Project)
Real-time surveillance system combining computer vision, cloud recognition and LLM-based automation on embedded hardware.
- Designed the architecture: YOLOv8 person/object detection, cloud-based facial recognition and LLM-generated alerts, deployed on Raspberry Pi 5
- Status: FYP-I complete and defended ✅ | FYP-II in progress 🚧
`YOLOv8` `Raspberry Pi 5` `Facial Recognition` `LLM Integration`

**PPE Detection System**
End-to-end computer vision pipeline for checking protective equipment compliance in real time.
- Fine-tuned YOLOv8n on a labeled 10-class PPE dataset: 40 epochs, then checked per-class precision/recall, then 10 more epochs of targeted fine-tuning
- Built a custom OpenCV pipeline for bounding boxes on images and video, served through a Flask app with upload-and-detect
`YOLOv8` `OpenCV` `Flask` `Object Detection`

**U-Net Image Segmentation**
Pixel-level human body segmentation.
- Pretrained ResNet34 encoder (`segmentation_models_pytorch`), trained on a ~2,500-image COCO subset with augmentation
`PyTorch` `U-Net` `ResNet34` `COCO Dataset`

**Line-Following / Maze-Solving Robot**
PID-controlled robot for line following and maze navigation.
- Arduino Uno + TCRT5000 IR sensors + L298N motor driver
`Arduino Uno` `PID Control` `TCRT5000` `L298N`

---

### Connect with me
- Email: muhammadzahan12@hotmail.com
- LinkedIn: [linkedin.com/in/zahan-zahid-1b9684290](https://www.linkedin.com/in/zahan-zahid-1b9684290)
