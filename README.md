# People Fall Detection using YOLOv11-Pose + DeepSort

This project implements **real-time fall detection** using [YOLOv11-Pose](https://github.com/ultralytics/ultralytics) for human pose estimation combined with the **DeepSort tracker** for multi-person tracking. It detects people in video streams, draws skeletons, and identifies potential falls based on pose analysis.

---

## 🚀 Features
- **YOLOv10-Pose integration** for 17-keypoint human skeleton detection.
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
git clone https://github.com/Mazen-Ahmed12/people-fall-detection-using-Yolov10-pose-Deepsort.git
cd people-fall-detection-using-Yolov10-pose-Deepsort
