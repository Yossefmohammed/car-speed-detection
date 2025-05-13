# Car Speed Detection System

A computer vision-based system for detecting and tracking vehicles while measuring their speed using YOLOv8.

## Overview

This project implements a real-time vehicle detection and speed measurement system using YOLOv8, a state-of-the-art object detection model. The system can:
- Detect vehicles in video streams
- Track vehicles across frames
- Calculate vehicle speeds
- Count vehicles passing through a defined area

## Features

- Real-time vehicle detection using YOLOv8
- Vehicle tracking and speed calculation
- Vehicle counting functionality
- Support for video streams and recorded videos
- Configurable detection zones and speed measurement parameters

## Requirements

- Python 3.8+
- OpenCV
- YOLOv8
- NumPy
- Other dependencies (see requirements.txt)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/car-speed-detection.git
cd car-speed-detection
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Download the YOLOv8 model weights and place them in the appropriate directory.

## Usage

1. Run the main script:
```bash
python car_counting_and_speed_YOLOV8.py
```

2. Configure the detection zone and speed measurement parameters in the script.

3. The system will process the video stream and display:
   - Vehicle detections
   - Speed measurements
   - Vehicle counts

## Project Structure

- `car_counting and speed_YOLOV8.ipynb`: Main Jupyter notebook containing the implementation
- `data-trackercode-you will need.txt`: Contains link to additional resources
- Additional model weights and configuration files

## Contact Information

For any questions or support, please contact:

- Email: ypssefmohammedahmed@gmail.com
- Phone: +20 112 607 8938

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- YOLOv8 team for the excellent object detection model
- OpenCV community for computer vision tools and resources
