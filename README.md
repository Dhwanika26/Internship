# Internship
Project Description: Real-time Face Alignment Monitoring System

Overview:
This project is a real-time face alignment monitoring system implemented in Python using the OpenCV library. The system captures video from the default camera (Webcam) and employs a Haar Cascade Classifier to detect faces in each frame. The main goal is to provide visual feedback on the alignment of the detected face with respect to the center of the video frame.

Key Features:
1. Face Detection:
   - Utilizes the Haar Cascade Classifier to identify faces in the video stream.
   - Draws rectangles around detected faces for visual representation.

2. Alignment Visualization:
   - Calculates the center of both the detected face and the video frame.
   - Draws a crosshair at the center of the frame for reference.
   - Marks the center of the detected face with a smaller circle.

3. Alignment Error Calculation:
   - Determines the alignment error by computing the difference between the centers of the detected face and the video frame.

4. Real-time Feedback:
   - Displays the alignment error on the video frame in real-time.
   - The alignment error includes both X and Y components.

5. User Interaction:
   - The system runs continuously until the user presses the 'q' key, at which point it gracefully exits.

How to Use:
1. Ensure that Python and OpenCV are installed on the system.
2. Clone the repository and execute the provided script.
3. The webcam will activate, and the real-time face alignment monitoring system will begin.
4. Observe the video feed with face detection rectangles, alignment crosshair, and error information.
5. Press the 'q' key to exit the application.

Dependencies:
- This project relies on the OpenCV library for computer vision tasks. Ensure that OpenCV is installed before running the script.

Purpose:
This project is designed to serve as a tool for monitoring face alignment in real-time, providing valuable insights for applications such as human-computer interaction, user experience testing, and facial recognition system development.

Note:
Make sure to credit the OpenCV library, as this project utilizes Haar Cascade Classifier for face detection. The system's modular design allows for easy integration into existing projects or as a standalone application for face alignment analysis.
