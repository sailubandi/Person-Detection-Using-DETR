# Person-Detection-Using-DETR


# 🧍 Smart Person Detection in Videos using DETR & Vision Transformers

🚀 A deep learning-powered project that detects and counts people in videos using **Facebook’s DETR (DEtection TRansformer)**. It overlays bounding boxes and statistics onto each frame, generating an enhanced output video.

---

## 📌 Overview

This project implements a **real-time object detection pipeline** that identifies persons in video frames using **Vision Transformers**. It utilizes **DETR-ResNet-50** from Hugging Face Transformers and processes input videos to highlight detected persons with bounding boxes and summary overlays.

---

## 🎯 Features

- ✅ Transformer-based person detection using `facebook/detr-resnet-50`
- 📹 Frame-wise detection with adjustable sampling interval
- 🧍 Bounding box overlays only for "person" class
- 🖼️ Annotated frame info panel (count & frame number)
- 🎞️ Outputs enhanced video with all detections

---

## 🧠 How It Works

1. **Upload a video** using Colab file uploader.
2. **Extract every N-th frame** (default is every 10 frames).
3. **Run DETR model** to detect persons.
4. **Draw bounding boxes** on the frame.
5. **Overlay detection stats** (person count + frame number).
6. **Export processed video** (`output.mp4`) with all annotations.

---

## 🛠️ Tech Stack

| Tool / Library       | Purpose                                 |
|----------------------|-----------------------------------------|
| `transformers`       | Pretrained DETR model & image processor |
| `timm`               | Vision model support (optional)         |
| `opencv-python`      | Frame extraction & video generation     |
| `torch`              | Model inference                         |
| `Pillow (PIL)`       | Image processing                        |
| `numpy` & `pandas`   | Data handling                           |

---

## 🧪 Example Output

Each frame in the output video contains:
- ✅ Bounding boxes around detected persons
- 📊 A top info panel with:
  - `Persons detected: [count]`
  - `Frame: [frame_number]`

---

## 📁 File Structure
📦 person-detection-DETR
┣ 📜 your_script.ipynb / .py
┣ 📼 input_video.mp4 (uploaded)
┣ 📼 output.mp4 (generated)
┗ 📜 README.md

---

## 📈 Applications

- 🛡️ Surveillance & Security Automation  
- 👥 Crowd Density Estimation  
- 🏙️ Smart City Infrastructure  

---

## 💡 Future Enhancements

- 🔁 Real-time webcam detection
- 🧍‍♂️ Multi-class object detection (e.g., car, bicycle)
- 🏃‍♂️ Person tracking using DeepSORT or ByteTrack
- 🌐 Web app deployment with Streamlit or Flask
- 📱 Edge deployment (Jetson Nano, Android)

---

## 📜 License

MIT License — Free to use and modify

---

## 📬 Contact

Have suggestions or questions?  
📧 Email me at: `sailubandi33@gmail.com`

