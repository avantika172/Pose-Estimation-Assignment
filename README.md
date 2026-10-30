# Human Pose Estimation using YOLOv8

## Project Overview
This project implements Human Pose Estimation using the pretrained YOLOv8 Pose model.

The model detects 17 human body keypoints based on the COCO dataset.

## Technologies Used
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- NumPy
- Jupyter Notebook

## Implementation
1. Load the pretrained YOLOv8 Pose model.
2. Read a 5–10 second input video.
3. Detect human body keypoints.
4. Extract the coordinates and confidence scores of the 17 COCO keypoints.
5. Generate two separate output videos.

## Output Videos

**Output 1:** Black keypoints on a white background.

**Output 2:** White keypoints on a black background.

## How to Run
1. Install the required Python libraries.
2. Open `pose_estimation.ipynb` in Jupyter Notebook.
3. Place `input_video.mp4` in the project folder.
4. Run all notebook cells.

## Author
Pose Estimation Assignment
