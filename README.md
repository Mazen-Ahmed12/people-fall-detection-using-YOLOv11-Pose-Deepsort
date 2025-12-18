# People Fall Detection using YOLOv11-Pose + DeepSort

This project implements **real-time fall detection** using [YOLOv11-Pose](https://github.com/ultralytics/ultralytics) for human pose estimation combined with the **DeepSort tracker** for multi-person tracking. It detects people in video streams, draws skeletons, and identifies potential falls based on pose analysis.

---

## 🚀 Features
- **YOLOv11-Pose integration** for 17-keypoint human skeleton detection.
- **DeepSort tracking** to maintain consistent IDs across frames.
- **Fall detection logic**: compares shoulder vs. lower-body keypoints to flag when a person may have fallen.
- **Video output** with bounding boxes, skeletons, and fall alerts.
- Configurable confidence thresholds for both detection and pose estimation.

---

## 📂 Project Structure
- `people fall detection using YOLOv11-Pose+Deepsort.ipynb` → the googleColab file for detection, skeleton drawing, and fall detection.
- `cam7.avi` → Example input video (replace with your own).  

---

## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/Mazen-Ahmed12/people-fall-detection-using-Yolov11-pose-Deepsort.git
cd people-fall-detection-using-Yolov11-pose-Deepsort
```
## OR 

## You can Run the notebook on (Google Colab) 
1. Download the notebook and Open it in Colab
2. Make sure you have GPU runtime enabled:
    - Go to **Runtime → Change runtime type → GPU**
3. Run the cells step by step:
   - Install dependencies (YOLO, MediaPipe, DeepSort, OpenCV)
   - upload the model on google colab and change the directory in the code the path of the model(custome - YOLO) 
   - upload the video you want to run the detection on and change the path of the video in the code and run the detection 
