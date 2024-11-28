Description:
This project implements a lane detection system using computer vision techniques in Python with OpenCV. 
The system processes video footage to identify and highlight lane markings, making it useful for applications such as autonomous driving and driver assistance systems.
Main Functions:
draw_the_lines(image, lines): Draws the detected lines on the image.
region_of_interest(image, region_points): Masks the image to focus on the region of interest.
get_detected_lanes(image): Detects and highlights lane markings on the image frames.
Usage:
Place your video file (e.g., lane_detection_video.mp4) in the project directory.
Run the lane_detection.py script:
