# Football Analysis System using YOLOv8, KMeans, Optical Flow, and Perspective Transformation
![Capture](https://github.com/user-attachments/assets/1bb2c2b0-47a8-43fe-9fc9-3ad3940a250e)


This project leverages advanced machine learning, computer vision, and deep learning techniques to analyze football games, detecting and tracking players, referees, and footballs in real-time. By using **YOLOv8**—a state-of-the-art object detection model—and fine-tuning it with custom datasets, this system enhances tracking accuracy and delivers deep insights into player performance.

The system also applies **KMeans clustering** to assign players to teams based on the colors of their t-shirts, and uses **optical flow** to detect camera movement, ensuring accurate measurement of player movement. With **perspective transformation**, it converts movement from pixel space to real-world units (meters), calculating each player's speed and distance covered.

## Key Features:
1. **Object Detection & Tracking:** Detect players, referees, and footballs using **YOLOv8**, track objects across frames, and train a custom detector for more accurate results.
2. **Team Assignment via Color Segmentation:** Use **KMeans** clustering for pixel segmentation to accurately assign players to teams based on t-shirt colors.
3. **Camera Movement Detection:** Employ **optical flow** to detect camera movement and compensate for it during tracking.
4. **Perspective Transformation:** Utilize **OpenCV's perspective transformation** to estimate real-world depth and perspective, allowing for accurate player movement measurement in meters.
5. **Speed & Distance Estimation:** Calculate player speed and distance covered based on real-world measurements.
   
## Datasets:
- [Kaggle Football Dataset](https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout/data?select=clips)
- [Roboflow Football Dataset](https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc/dataset/1)
## Installation:
1. Clone this repository:  
   ```bash
   git clone https://github.com/M-9acem/Football_Analysis.git
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Download and prepare datasets using the links provided above.

## Usage:
- Run Project:
  ```bash
  python main.py
  ```


## Key Concepts:
- **YOLOv8 Object Detection** – Detect and track players, referees, and footballs.
- **KMeans Clustering** – Segment and assign players based on t-shirt colors.
- **Optical Flow** – Track camera movement between frames.
- **Perspective Transformation** – Calculate player movement in real-world units.
- **Speed & Distance Estimation** – Measure player performance metrics like speed and distance covered.

## Video Walkthrough:
Check out the full project walkthrough and explanation on YouTube:

[YouTube Walkthrough](https://www.youtube.com/watch?v=XYZ](https://www.youtube.com/watch?v=neBZ6huolkg)
Big thanks to @abdullahtarek
