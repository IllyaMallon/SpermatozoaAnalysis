## Spermatozoa Analyzer

Computer Vision-Based Sperm Tracking & Motility Analysis
<br>Spermatozoa Analyzer is a computer vision-based tool for automated sperm tracking and motility analysis. Using OpenCV, TensorFlow, and Tkinter, it detects, tracks, and evaluates sperm movement from video, providing key fertility metrics (VCL, VSL, VAP, LIN, PPM). <br>Features real-time visualization, reporting, and UI-based calibration.

## 🎥 Demo  
Below is a short demo of the Spermatozoa Analyzer in action:

<p align="center">
  <img src="https://github.com/user-attachments/assets/47c0f61c-8a2a-45b3-8a3f-55fb5822870e" alt="Spermatozoa Analyzer Demo" width="1000">
</p>

## What's Inside the App?

<br>🎥 Video Processing
<br>✅ Loads and preprocesses video frames
<br>✅ Converts to grayscale, applies thresholding, and removes noise
<br>✅ Uses background subtraction for better detection

<br>📍 Sperm Detection & Tracking
<br>✅ Identifies sperm using contour detection
<br>✅ Tracks movement across frames with Kalman filters
<br>✅ Assigns unique colors to each tracked sperm

<br>📊 Motion & Velocity Analysis
<br>✅ Computes key sperm motility metrics:

* VCL (Curvilinear Velocity)
* VSL (Straight-Line Velocity)
* VAP (Average Path Velocity)
* LIN, WOB, STR (Movement quality)

<br>📈 Statistical Evaluation & Reporting
<br>✅ Determines Percent Progressive Motility (PPM)
<br>✅ Categorizes sperm motility into:
* Not Motile
* Low
* Moderate
* High Motility


✅ Provides health scores based on fertility standards
<br>✅ Generates text-based reports

<br>🖥️ UI & User Interaction (Tkinter-Based)
<br>✅ Manual scale calibration using a drawing tool
<br>✅ Supports zooming & panning for better visualization
<br>✅ Displays real-time processed video & statistics

<br>📡 Grid-Based Analysis
<br>✅ Applies a grid overlay to divide the sample area
<br>✅ Ensures accurate sperm count estimations

<br>🛠 Tech Stack
* Python (Core Logic)
* OpenCV (Computer Vision & Image Processing)
* TensorFlow (ML-Based Tracking & Analysis)
* Tkinter (GUI for Calibration & Visualization)
* NumPy, SciPy (Data Handling & Mathematical Calculations)
