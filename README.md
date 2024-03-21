This script captures video from the specified webcam (usually camera index 1), detects faces using a pre-trained Haar cascade classifier (faces.xml), and draws bounding boxes around the detected faces in real-time. It displays the modified video with bounding boxes in a window titled "Recording". The user can press the 'q' key to stop the recording. The recorded video with bounding boxes is saved as output.avi in the project folder.

Install OpenCV:

``pip install opencv-python``

Place the Haar cascade classifier file (faces.xml) in the project folder.

Run the script:

``python real_time_face_detection_webcam.py``

Press the 'q' key to stop the recording and exit the application.
