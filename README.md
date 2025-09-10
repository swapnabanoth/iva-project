#  Pet Patrol: Detecting Cats and Dogs using YOLOv5

This project uses **YOLOv5 (You Only Look Once)** for real-time object detection of **cats 🐱 and dogs 🐶** in images and videos.  
The implementation is done in **Google Colab** with PyTorch and OpenCV, allowing you to upload images/videos and detect pets with bounding boxes.


##  Features
- Detect **cats** and **dogs** from images.
- Detect pets in **videos** (frame-by-frame).
- Bounding boxes with confidence scores.
- Works in **real-time inference** (limited by hardware).
- Implemented in **Google Colab** (no setup needed locally).

---

## Tech Stack
- **YOLOv5** (Ultralytics)
- **Python 3.12**
- **PyTorch 2.8.0**
- **OpenCV**
- **Pandas & NumPy**
- **Matplotlib**
- **Google Colab**


##  How to Run

### 1️ Clone YOLOv5 and Install Dependencies
```bash
!git clone https://github.com/ultralytics/yolov5
%cd yolov5
!pip install -r requirements.txt

