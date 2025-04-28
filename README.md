# Vehicle Speed Detection System

This project implements a **Vehicle Speed Detection System** using **OpenCV**, **Python**, and **Euclidean Distance Tracking**. The system processes video streams of traffic, detects vehicles, calculates their speed, and identifies vehicles exceeding a specified speed limit. The project also captures images of vehicles that violate the speed limit and generates reports on speed violations.

---

## Features
- **Real-time Vehicle Tracking**: Detect and track vehicles in a video stream.
- **Speed Calculation**: Calculate the speed of each vehicle by analyzing the time taken for the vehicle to cross two reference lines in the video frame.
- **Speed Limit Violation Detection**: Identify vehicles exceeding the set speed limit (default: 80 km/h).
- **Vehicle Image Capture**: Capture images of vehicles exceeding the speed limit for documentation and further analysis.
- **Data Logging**: Record the speed of vehicles and whether they exceeded the speed limit in a text file.
- **Summary Reports**: Generate a summary of detected vehicles, the number of violations, and the total number of vehicles processed.

---

## Prerequisites

- Python 3.x
- OpenCV
- Numpy

---

## Installation

### Step 1: Clone the Repository
Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/yourusername/VehicleSpeedDetection.git
cd VehicleSpeedDetection
