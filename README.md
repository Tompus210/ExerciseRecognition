# Exercise Recognition with YOLOv8 and OpenCV

This project recognises fitness exercises (e.g. squats, push-ups, pull-ups) live via camera with YOLOv8 + OpenCV and classifies them using machine learning.

## Setup

```bash
git clone https://github.com/Tompus210/ExerciseRecognition.git
cd ExerciseRecognition
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
pip install -r requirements.txt
```

Download YOLOv11 Pose model:
https://docs.ultralytics.com/de/tasks/pose/

## Video Dataset

Training and evaluation videos used in this project are available at the following location:

[Access shared video folder (OneDrive)](https://mci4meat-my.sharepoint.com/:f:/g/personal/pt3331_mci4me_at/Elu0N5NN4KtIuBGZawRI4BUBPEyqMla_U_WJ1ntAXD8PAg?e=rRVECU)