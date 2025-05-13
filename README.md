# PREDICTION-OF-ROAD-LANE
This project implements a real-time lane detection system that processes video input to identify and highlight lane boundaries on roads.  It also distinguishes between left and right lanes and identifies their types (solid or dashed) based on pixel density.
Using computer vision techniques such as Canny edge detection, Gaussian blurring, region masking, and Hough Line Transform, the system detects and overlays solid and dashed lane markings on each video frame.
The solution is designed to provide a robust base for autonomous vehicle systems, driver-assistance technologies, and advanced visual navigation modules.


# KEY FEATURES:

1.  **Edge Detection:** Detects lane boundaries using the Canny algorithm.

2.  **Region of Interest (ROI):** Focuses only on the part of the image most likely to contain lanes (road surface).

3.  **Hough Transform:** Accurately detects line segments representing lanes.

4.  **Perspective Transformation:** Warps the road image to a bird’s-eye view for better lane analysis.

5.  **Histogram Analysis:** Identifies peak lane positions from the lower half of the image.

6.  **Lane Type Classification:** Differentiates between solid and dashed lines based on pixel density.

7.  **Visual Feedback:** Combines intermediate outputs (edge map, mask, warped view) into a single collage for step-by-step analysis.

8.  **Real-Time Processing:** Works with video input and outputs processed video with overlaid lane data.

#Tech Stack:

1.  **Language:** Python

2.  **Libraries:** OpenCV, NumPy

3.  **Algorithmic Concepts:** Hough Line Transform, Perspective Warping, Edge Detection, Histogram Analysis

 # Input & Output:
 
1.  Input: Road-driving video (e.g., whiteline.mp4)
   
2.  Output: Annotated video showing detected lanes and classification text (solid or dashed, left or right).
