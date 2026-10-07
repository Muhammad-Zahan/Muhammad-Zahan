# Hi, I'm Zahan

**Embedded Systems | Computer Vision | Local AI**

I have a background in embedded systems and computer vision. I'm building an AI-powered security system as my final year project, and I like testing how small language models run on everyday hardware like a laptop CPU. I also do freelance work in logo design and website customization.

---

## Final Year Project

### AI-Powered Smart Security & Home Automation
A real-time surveillance system that combines computer vision, cloud recognition and LLM-based automation on embedded hardware.

- YOLOv8 for person and object detection
- Cloud-based facial recognition
- LLM-generated alerts so notifications are easy to read
- Deployed on Raspberry Pi 5

**Status:** FYP-I complete and defended, FYP-II in progress

**Tech:** YOLOv8, Raspberry Pi 5, Facial Recognition, LLM Integration

---

## Other Projects

### Qwen 2.5 (1.5B, FP16) on a Laptop CPU
Ran a small language model on CPU only, using OpenVINO GenAI.
- About 7.9 tokens/sec with 834 ms time to first token
- Tuned temperature, top_p, top_k and prompt window
- Also tested INT8, INT4 and Gemma 3 1B

**Tech:** OpenVINO, Qwen 2.5, Python

### Local AI Email Classifier (in progress)
Marks Gmail emails as IMPORTANT or NOT IMPORTANT with a short reason. Everything runs locally.
- Read-only Gmail access, extracts sender, subject, date and body
- Flask API checks urgent keywords first, and only calls the model if none match

**Tech:** Gmail API, Flask, OpenVINO, Qwen 2.5

### PPE Detection System
Real-time check for protective equipment compliance.
- Fine-tuned YOLOv8n on a 10-class dataset (40 epochs, per-class review, then 10 more epochs)
- Custom OpenCV pipeline for images and video
- Flask app with upload-and-detect

**Tech:** YOLOv8, OpenCV, Flask

### U-Net Image Segmentation
Pixel-level human body segmentation.
- Pretrained ResNet34 encoder, trained on a ~2,500-image COCO subset with augmentation

**Tech:** PyTorch, U-Net, ResNet34, COCO

### Line-Following / Maze-Solving Robot
PID-controlled robot built with Arduino Uno, TCRT5000 IR sensors and an L298N motor driver.

---

## Technical Skills

- **Languages:** Python, C/C++, JavaScript, MATLAB
- **Embedded:** Arduino, Raspberry Pi 5, PIC18F452, ESP32, NI myRIO/LabVIEW
- **AI/ML:** YOLOv8, U-Net, Transfer Learning, OpenCV, PyTorch
- **Local LLMs:** OpenVINO GenAI, Ollama, Qwen 2.5, Gemma 3, FP16/INT8/INT4 quantization
- **Web/Backend:** Flask, SQLite, Bootstrap 5
- **Tools:** Git, GitHub

---

## Contact

- Email: muhammadzahan12@hotmail.com
- LinkedIn: [linkedin.com/in/zahan-zahid-1b9684290](https://www.linkedin.com/in/zahan-zahid-1b9684290)
