# PROJECT-
Soccer Player Re-identification using YOLOv5 🏃‍♂️⚽

Author: Kondepudi Sion RaniLinkedIn: linkedin.com/in/kondepudi-sion-rani

📦 Project Structure

Soccer-ReID-YOLOv5/
├── yolov5/                     # Cloned YOLOv5 repo
├── best.pt                    # Trained model weights
├── 15sec_input_720p.mp4       # Input soccer video
├── reid_output.mp4            # Output video with re-identified players
├── Soccer_ReID_YOLOv5.ipynb   # Main code file (or .py script)
├── README.md                  # Project documentation
├── Report.docx / Report.pdf   # Brief report of methodology
└── screenshots/               # Example output frame(s)

⚙️ Setup Instructions

1. Clone YOLOv5

git clone https://github.com/ultralytics/yolov5
cd yolov5

2. Install Required Packages

Use Anaconda or Python ≥3.8

pip install -r requirements.txt

Make sure torch, torchvision, opencv-python, matplotlib, etc., are installed.

3. Place Required Files

best.pt – Custom trained YOLOv5 model.

15sec_input_720p.mp4 – Input test video.

Place both in root directory.

4. Run the Code

python Soccer_ReID_YOLOv5.py

OR run Soccer_ReID_YOLOv5.ipynb in Jupyter Notebook.

Output video reid_output.mp4 will be generated in the current directory.

🧠 Project Overview

This project performs Soccer Player Re-identification using a custom-trained YOLOv5 model.

Key Features

Detects and tracks individual soccer players.

Assigns consistent unique IDs across frames.

Outputs a video with bounding boxes and labels.

🧪 Techniques Used

YOLOv5 for real-time object detection

IOU-based tracking logic for Re-ID

OpenCV for frame handling and video output

Matplotlib for optional frame visualization

📈 Results

Successfully tracked and labeled players in short clips.

Output video shows boxes and IDs updated frame by frame.

📌 Challenges & Future Work

Accuracy drops when players overlap.

Could use Deep SORT or BYTETrack for better tracking.

Larger dataset would help training improve performance.

✅ Final Notes

Make sure:

best.pt is present in your working directory.

Run in an environment where GPU acceleration (optional) is available.

🎉 You're ready to track soccer players like a pro!

Soccer Player Re-Identification using YOLOv5 + Python – detects and tracks players using bounding boxes.
