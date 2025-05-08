# TrackLane
# 🚗 Lane Lines Detection using OpenCV

This project demonstrates a computer vision pipeline to detect road lane lines in images and video streams using Python and OpenCV. It processes road frames through grayscale conversion, Gaussian blur, Canny edge detection, and Hough Line Transform to identify and overlay lane lines. It works for static images, videos, and real-time webcam feed.

---

## 🧠 Project Highlights

- Detects lane lines in road images and video footage.
- Real-time lane detection using live webcam.
- Uses OpenCV for image processing and frame manipulation.
- Visualizes intermediate steps using Matplotlib.
- Implemented and tested in Jupyter Notebook.

---

## 📌 Pipeline Overview

1. **Load input** (image, video, or camera).
2. **Convert to grayscale** and apply **Gaussian blur**.
3. **Detect edges** using **Canny edge detection**.
4. Define and **mask region of interest**.
5. Use **Hough Line Transform** to detect lane lines.
6. **Average and extrapolate** the detected lines.
7. Overlay the lane lines on the original frame.

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- MoviePy (for video processing)
- Jupyter Notebook

---

## 📷 Inputs Supported

- ✅ Static images (`.jpg`, `.png`)
- ✅ Video files (`.mp4`, `.avi`)
- ✅ Real-time video via webcam

---

## 🧪 Output

- Displays lane detection result with overlaid lines.
- Shows intermediate steps like edge detection and masked region.
- Works on both still images and continuous video frames.

---

## 📸 Example Output

![Example Output](output_example.jpg)


