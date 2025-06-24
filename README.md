# PROJECT-
Requirements

- Python 3.8+
- Anaconda or virtualenv (recommended)
- requirements.txt from YOLOv5 repository

Installation

1. Clone the YOLOv5 repository and install dependencies:
    git clone https://github.com/ultralytics/yolov5
    cd yolov5
    pip install -r requirements.txt

Model and Files

- Place your trained model weights file `best.pt` inside the yolov5 directory.
- Ensure the input video `15sec_input_720p.mp4` is also in the same directory.

Running the Script

Run the Python script using:
    python player_reid.py
Output will be saved as `reid_output.mp4`.

