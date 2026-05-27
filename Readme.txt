# Smart Mirror for Stroke Analysis using Raspberry Pi

## Overview
The Smart Mirror for Stroke Analysis is a real-time healthcare monitoring system developed using Raspberry Pi, Computer Vision, and OpenCV. The system detects facial asymmetry such as mouth deviation and eye imbalance, which are common early indicators of stroke symptoms.  

The project continuously captures facial images using a Raspberry Pi camera and analyzes facial features using Haar Cascade algorithms. Based on the detected asymmetry level, the system displays risk alerts and warning messages on a 16x2 I2C LCD display.

This project aims to support early stroke detection and improve healthcare accessibility through low-cost embedded AI technology.

---

# Features
- Real-time face detection
- Mouth asymmetry detection
- Eye asymmetry analysis
- Stroke risk score calculation
- LCD display output monitoring
- Alarm and warning indication
- Brightness checking for reliable detection
- Lightweight Raspberry Pi implementation
- Real-time risk monitoring using EMA smoothing

---

# Hardware Components Used

| Component | Description |
|---|---|
| Raspberry Pi 3B+ | Main processing unit |
| Raspberry Pi Camera Rev 1.3 | Captures facial images |
| 16x2 I2C LCD Display | Displays alerts and risk values |
| 16GB SD Card | Stores OS and project files |
| Power Supply | Provides power to Raspberry Pi |

---

# Software Requirements
- Python 3
- OpenCV
- NumPy
- RPLCD
- smbus2

---

# Python Libraries Used

```bash
pip install opencv-python numpy RPLCD smbus2