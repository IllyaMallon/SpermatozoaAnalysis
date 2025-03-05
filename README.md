## Spermatozoa Analyzer

Computer Vision-Based Sperm Tracking & Motility Analysis
<br>Spermatozoa Analyzer is a computer vision-based tool for automated sperm tracking and motility analysis. Using OpenCV, TensorFlow, and Tkinter, it detects, tracks, and evaluates sperm movement from video, providing key fertility metrics (VCL, VSL, VAP, 
LIN, WOB, STR, BCF, ALH, PPM). <br>Features real-time visualization, reporting, and UI-based calibration.

## 🎥 Demo  
Below is a short demo of the Spermatozoa Analyzer in action:

https://github.com/user-attachments/assets/ef06721e-287e-412e-bc5a-fddfadb2f197

### Legend

| **Color**          | **Description**               |
|---------------------|-------------------------------|
|  **Green**        | Moving Spermatozoa            |
|  **Red**          | Non-Moving Spermatozoa        |
|  **White**        | Collisions Between Spermatozoa|
| **Coloured Lines**  | Spermatozoa Tracks            |

## What's Inside the App Prototype?

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

## Reference Links 
Alabdulla, A. H., Haşıloğlu, A., & Aksu, E. H. (2021). A robust sperm cell tracking algorithm using uneven lighting image fixing and improved branch and bound algorithm. IET Image Processing, 15(9), 2068–2079. https://doi.org/10.1049/ipr2.12178

Kheirkhah, F. M., Mohammadi, H. R. S., & Shahverdi, A. (2019). Efficient and robust segmentation and tracking of sperm cells in microscopic image sequences. IET Computer Vision, 13(5), 489–499. https://doi.org/10.1049/iet-cvi.2018.5662

Rodríguez-Montaña, D., & Roa, E. (2017). Objective assessment of bull sperm motility parameters using computer vision algorithms. African Journal of Biotechnology, 16(37), 1871–1881. https://doi.org/10.5897/AJB2017.16122



