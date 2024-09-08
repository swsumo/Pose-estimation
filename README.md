# Pose Estimation Project

This project implements a basic pose estimation model using OpenCV (`cv2`) and MediaPipe (`mediapipe`). The script processes a given video and detects key body landmarks, highlighting the points of the body that are moving throughout the video.

## Project Structure

```
.
├── .idea
├── venv
├── bicep.mp4
├── pose_detection.py
└── pose_estimation.py
```

- **.idea/**: Contains configuration files for the project, mainly used by the IDE (e.g., PyCharm).
- **venv/**: Virtual environment folder containing all the necessary dependencies for the project.
- **bicep.mp4**: A sample video file that serves as the input for the pose estimation script.
- **pose_detection.py**: Script responsible for detecting and plotting the moving body landmarks.
- **pose_estimation.py**: Another script related to pose estimation (similar functionality or an alternative approach).

## Requirements

To run this project, you'll need the following Python packages:

- `opencv-python`
- `mediapipe`

You can install the required packages using pip:

```bash
pip install opencv-python mediapipe
```

## How to Use

1. **Input Video**: The project processes an input video file. In this example, `bicep.mp4` is used as the input video. You can replace this with any other video file by placing it in the same directory and modifying the script accordingly.

2. **Running the Script**: Use the following command to run the pose detection script:

```bash
python pose_detection.py
```

3. **Output**: The script will process the video and plot key points on the body parts that are moving, allowing you to visualize the detected poses.

## Explanation

- **OpenCV (`cv2`)**: Used for reading the video input, processing each frame, and displaying the output with the plotted key points.
- **MediaPipe (`mediapipe`)**: A machine learning framework utilized for detecting human body landmarks (e.g., shoulders, elbows, wrists, etc.) in each frame of the video.

## Future Work

- Integrate more advanced pose estimation techniques.
- Implement a front-end interface for easier video uploads and visualization.
- Expand the functionality to support real-time pose detection via webcam.


## Acknowledgements

- Thanks to the OpenCV and MediaPipe teams for their powerful libraries.
```

This `README.md` provides a clear and concise overview of the project, including its structure, usage, and future work. Let me know if you need further modifications!
 
