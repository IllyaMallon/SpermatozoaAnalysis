🚀 Spermatozoa Analyzer
Computer Vision-Based Sperm Tracking & Motility Analysis
Spermatozoa Analyzer is a computer vision-based tool for automated sperm tracking and motility analysis. Using OpenCV, TensorFlow, and Tkinter, it detects, tracks, and evaluates sperm movement from video, providing key fertility metrics (VCL, VSL, VAP, LIN, PPM). Features real-time visualization, reporting, and UI-based calibration.

🧐 What's Inside the App?
🎥 Video Processing
✅ Loads and preprocesses video frames
✅ Converts to grayscale, applies thresholding, and removes noise
✅ Uses background subtraction for better detection

📍 Sperm Detection & Tracking
✅ Identifies sperm using contour detection
✅ Tracks movement across frames with Kalman filters
✅ Assigns unique colors to each tracked sperm

📊 Motion & Velocity Analysis
✅ Computes key sperm motility metrics:

VCL (Curvilinear Velocity)
VSL (Straight-Line Velocity)
VAP (Average Path Velocity)
LIN, WOB, STR (Movement quality)
✅ Determines Percent Progressive Motility (PPM)
📈 Statistical Evaluation & Reporting
✅ Categorizes sperm motility into:

Not Motile, Low, Moderate, High Motility
✅ Provides health scores based on fertility standards
✅ Generates text-based reports
🖥️ UI & User Interaction (Tkinter-Based)
✅ Manual scale calibration using a drawing tool
✅ Supports zooming & panning for better visualization
✅ Displays real-time processed video & statistics

📡 Grid-Based Analysis
✅ Applies a grid overlay to divide the sample area
✅ Ensures accurate sperm count estimations

🛠 Tech Stack
Python (Core Logic)
OpenCV (Computer Vision & Image Processing)
TensorFlow (ML-Based Tracking & Analysis)
Tkinter (GUI for Calibration & Visualization)
NumPy, SciPy (Data Handling & Mathematical Calculations)
