# Color Detector

A simple OpenCV-based tool to detect the name of a color when you click on any pixel in an image.

## Features
- Click on any part of the image to get the closest matching color name.
- Uses a CSV file containing standard color names and RGB values.
- Fallback to default color data if `colors.csv` is not found.

## Setup
```bash
git clone https://github.com/yourusername/color-detector.git
cd color-detector
pip install -r requirements.txt
