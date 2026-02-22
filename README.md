# OpenCV-Dot-Detector

A lightweight Python project that uses Computer Vision to automate the counting of scattered objects based on color thresholds.

### How it works:
- **HSV Masking:** Converts images from BGR to HSV for robust color isolation.
- **Contour Mapping:** Uses `cv2.findContours` to identify and group colored pixels.
- **Automated Annotation:** Draws circles around detected objects for visual verification.

### Tech Stack:
- Python 3
- OpenCV
- NumPy
