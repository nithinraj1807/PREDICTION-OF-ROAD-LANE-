# PREDICTION-OF-ROAD-LANE
This project implements a real-time lane detection system that processes video input to identify and highlight lane boundaries on roads.  It also distinguishes between left and right lanes and identifies their types (solid or dashed) based on pixel density.
Using computer vision techniques such as Canny edge detection, Gaussian blurring, region masking, and Hough Line Transform, the system detects and overlays solid and dashed lane markings on each video frame.
The solution is designed to provide a robust base for autonomous vehicle systems, driver-assistance technologies, and advanced visual navigation modules.


# KEY FEATURES:
**Edge Detection:** Detects lane boundaries using the Canny algorithm.

**Region of Interest (ROI):** Focuses only on the part of the image most likely to contain lanes (road surface).

**Hough Transform:** Accurately detects line segments representing lanes.

**Perspective Transformation:** Warps the road image to a bird’s-eye view for better lane analysis.

**Histogram Analysis:** Identifies peak lane positions from the lower half of the image.

**Lane Type Classification:** Differentiates between solid and dashed lines based on pixel density.

**Visual Feedback:** Combines intermediate outputs (edge map, mask, warped view) into a single collage for step-by-step analysis.

**Real-Time Processing:** Works with video input and outputs processed video with overlaid lane data.
