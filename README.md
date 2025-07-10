# Licence Plate Detection and Recognition using YOLOv8 + EasyOCR

This project performs **vehicle license plate detection and recognition** using the **YOLOv8** model and the **EasyOCR** library.

---

## 🚀 How to Run the Project

Run the following command in your terminal:

```bash
python predictWithOCR.py model='best.pt' source='<input>'

| Input Type | Example              | Description               |
| ---------- | -------------------- | ------------------------- |
| 🎥 Video   | `source='demo.mp4'`  | Use a video file as input |
| 🖼️ Image  | `source='image.jpg'` | Use a single image file   |
| 📷 Webcam  | `source=0`           | Use your device's webcam  |


📁 Expected Project Structure

project/
├── predictWithOCR.py
├── best.pt
├── data/
│   └── images/
│       └── image.jpg
├── runs/
│   └── detect/
│       └── ...
