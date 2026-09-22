# Real-Time Object Detection with YOLOv8

This project uses Ultralytics YOLOv8 Large (`yolov8l.pt`) and OpenCV to detect objects from a webcam in real time.

## Requirements

- Python 3.8 or newer
- Webcam
- Windows, macOS, or Linux

## Installation

```bash
pip install ultralytics opencv-python
```

## Run the Application

```bash
python object_detection.py
```

The `yolov8l.pt` model will be downloaded automatically on the first run.

## Controls

- Press **Q** to quit the application.

## Model

This project uses:

- Model: YOLOv8 Large
- File: `yolov8l.pt`
- Framework: Ultralytics
- Input: Webcam frames
- Output: Annotated video with detected objects

For faster performance, replace `yolov8l.pt` with `yolov8n.pt`.

## Project Structure

```text
Object_detection/
├── object_detection.py
├── yolov8l.pt
└── README.md
```

## License

Review the Ultralytics licensing terms before using this model commercially.