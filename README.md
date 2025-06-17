# Exercise Recognition with YOLOv8 and OpenCV

This project recognises fitness exercises (e.g. squats, push-ups, pull-ups) from input videos with YOLOv11 + OpenCV and classifies them using machine learning.

## Setup: Clone the repository and create a virtual environment

```bash
git clone https://github.com/Tompus210/ExerciseRecognition.git
cd ExerciseRecognition
python3.11 -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
pip install --upgrade pip
pip install -r requirements.txt
```

Download YOLOv11 Pose model:
https://docs.ultralytics.com/de/tasks/pose/


## Video Dataset

Training and evaluation videos used in this project are available at the following location:

[Access shared video folder (OneDrive)](https://mci4meat-my.sharepoint.com/:f:/g/personal/pt3331_mci4me_at/Elu0N5NN4KtIuBGZawRI4BUBPEyqMla_U_WJ1ntAXD8PAg?e=rRVECU)


## Keypoint Index Mapping

Each frame contains 17 keypoints representing body joints detected by the pose estimation model. The following table maps the index to the corresponding body part:

| Index | Body Part       |
|-------|------------------|
| 0     | Nose             |
| 1     | Left Eye         |
| 2     | Right Eye        |
| 3     | Left Ear         |
| 4     | Right Ear        |
| 5     | Left Shoulder    |
| 6     | Right Shoulder   |
| 7     | Left Elbow       |
| 8     | Right Elbow      |
| 9     | Left Wrist       |
| 10    | Right Wrist      |
| 11    | Left Hip         |
| 12    | Right Hip        |
| 13    | Left Knee        |
| 14    | Right Knee       |
| 15    | Left Ankle       |
| 16    | Right Ankle      |
