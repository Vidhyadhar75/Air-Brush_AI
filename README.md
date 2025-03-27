# AirBrush-AI

## 📌 Project Overview
AirBrush-AI is a real-time computer vision application that allows users to draw using an optical flow-based tracking system. The project utilizes OpenCV to track movement and simulate an airbrush painting effect.

## 🚀 Features
- **Real-time tracking**: Uses Lucas-Kanade optical flow to follow hand movements.
- **Dynamic Drawing**: Supports continuous drawing with variable colors.
- **Airbrush Effect**: Simulates a soft brush stroke.
- **Interactive Controls**:
  - Press `E` to erase the canvas.
  - Press `C` to change colors.
  - Press `ESC` to exit.

## 📂 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Vidhyadhar75/Air-Brush-AI.git
   cd Air-Brush-AI
   ```
2. Install dependencies:
   ```bash
   pip install opencv-python numpy
   ```

## 🛠 Usage

Run the script:
```bash
python drawing.py
```

## 📊 How It Works
- Captures video from the webcam.
- Tracks initial mouse click to set the starting point.
- Uses **cv2.calcOpticalFlowPyrLK()** for motion tracking.
- Draws lines based on movement while adding a Gaussian blur for an airbrush effect.

## 🤖 Technologies Used
- OpenCV
- NumPy

## 📌 Contribution
Pull requests are welcome! Feel free to improve the drawing mechanics or add new brush styles.

![Screenshot 2025-03-27 150437](https://github.com/user-attachments/assets/06445420-00cc-4f09-94b3-07cd527dafd1)


