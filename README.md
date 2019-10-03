# Hand Gestures Recognition Tool
A simple machine learning model built to recognize hand gestures. Implemented by designing an image processor to remove redundant information and match the input format of the model.

### Technologies used:
OpenCV, Python

## Implementation
· Firstly frames are captured and then ROI(Region of insterest) is extracted:<br>
    Image is converted into grayscale and then Gaussian Blur is used.
    After that thresholding is done.<br><br>
· Largest contour is found to get area of hand and then convex hulls are drawn.<br><br>
· Next step is to find convexity defects in the extracted frame.<br><br>
· Using these defects the number of fingers is calculated and then message is displayed accordingly.
