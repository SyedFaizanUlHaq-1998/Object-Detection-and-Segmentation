# Object-Detection-and-Segmentation

This project demonstrates real-time object detection and segmentation using the YOLO (You Only Look Once) deep learning model. The implementation leverages the YOLO model for recognizing and annotating objects in a live video feed from a webcam. The results are displayed in a fullscreen window with annotated visuals.

---

## Features

- **Real-time Object Detection**: Captures video frames from the webcam and processes them instantly.
- **YOLO Integration**: Utilizes the YOLO model for accurate object detection and segmentation.
- **Fullscreen Visualization**: Displays the output in a fullscreen window for enhanced visibility.
- **Interactive Controls**: Allows users to exit the application by pressing the `q` key.

---

## Prerequisites

Before running the code, ensure you have the following:

### Hardware Requirements
- A computer with a webcam.
- Moderate GPU for faster real-time processing (optional but recommended).

### Software Requirements
- Python 3.7 or higher.
- Required Python libraries:
  - `ultralytics`
  - `opencv-python`

To install the required libraries, use:
```bash
pip install ultralytics opencv-python
```

---

## Setup and Usage

1. **Clone the Repository**
   ```bash
   git clone <repository_url>
   cd Object-Detection-and-Segmentation
   ```

2. **Download the YOLO Model**
   - Ensure the model file (`yolo11n.pt`) is available in the same directory as the script. You can either download a pre-trained YOLO model or train your custom model using the [Ultralytics YOLO framework](https://github.com/ultralytics/ultralytics).

3. **Run the Code**
   - Execute the script with the following command:
     ```bash
     python object_detection.py
     ```
   - Replace `object_detection.py` with the actual filename of the script.

4. **Interactive Commands**
   - The program will run in fullscreen mode, showing the detected objects in the live webcam feed.
   - Press the `q` key to exit the application.

---

## How It Works

1. **Loading the Model**: The script initializes the YOLO model using the `ultralytics` library.
2. **Capturing Video**: The webcam feed is captured frame by frame using OpenCV.
3. **Processing Frames**: Each frame is passed through the YOLO model for detection and segmentation.
4. **Visualization**: Detected objects are annotated, and the output is displayed in a fullscreen window.
5. **Interactive Exit**: Users can terminate the application by pressing the `q` key.

---

## Limitations

- Requires a webcam for real-time functionality.
- Performance may vary based on system specifications, especially without a GPU.

---

## Future Enhancements

- Add support for external video files or IP cameras.
- Implement functionality to save annotated video outputs.
- Provide model customization for specific datasets.

---

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it.

---

## Acknowledgments

- [Ultralytics](https://github.com/ultralytics/ultralytics) for the YOLO framework.
- [OpenCV](https://opencv.org/) for video capture and visualization.

---

This README file provides all the necessary information for understanding and using your project effectively. Let me know if you need further modifications or additional sections!
