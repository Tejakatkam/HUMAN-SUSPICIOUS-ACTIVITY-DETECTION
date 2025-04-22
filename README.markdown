# Suspicious Activity Detection from CCTV Footage

This repository contains a Python-based application for detecting suspicious activities in examination halls using CCTV footage. The system leverages computer vision and deep learning to identify behaviors such as abnormal head movements, unauthorized position changes, and student interactions.

## Features
- Upload and process CCTV footage.
- Generate individual frames from video input.
- Detect suspicious activities using a pre-trained ResNet model.
- Display results in a graphical user interface (GUI).

## Requirements
- **Python**: 3.7 or higher.
- **Libraries**:
  - `opencv-python`: For video frame extraction (`pip install opencv-python`).
  - `imutils`: For image path handling (`pip install imutils`).
  - `matplotlib`: For potential visualization (`pip install matplotlib`).
  - `imageai`: For custom image prediction (`pip install imageai`).
  - `tkinter`: For GUI (included with Python).
- **Files**: `model.h5` and `model_class.json` (pre-trained model and labels) must be placed in the project directory.

## Installation
1. Clone the repository:
   ```bash
   git clone hhttps://github.com/Tejakatkam/HUMAN-SUSPICIOUS-ACTIVITY-DETECTION.git
   ```
2. Navigate to the project directory:
   ```bash
   cd suspicious-activity-detection
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Ensure `model.h5` and `model_class.json` are in the directory.

## Usage
1. Run the application:
   ```bash
   python main.py
   ```
2. Use the GUI to:
   - Upload CCTV footage via the "Upload CCTV Footage" button.
   - Generate frames with "Generate Frames."
   - Detect suspicious activities with "Detect Suspicious Activity Frame."
3. View results in the text areas.

## License
[MIT License] - See the LICENSE file for details.

## Contributing
Contributions are welcome. Please fork the repository and submit pull requests.

## Contact
For issues or questions, contact [tejakatkam2907@gmail.com].
