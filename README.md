# FaceFlare
- This project demonstrates basic facial feature detection using OpenCV, including face, smile, and eye detection. The code utilizes pre-trained Haar Cascade classifiers to identify and annotate these features in real-time through a webcam feed.
- This project was created as a part of learning Artificial Intelligence and Machine Learning concepts, focusing on computer vision techniques using OpenCV.
# Overview
- Captures video from the default webcam.
- Converts each frame to grayscale for better processing.
- Detects faces using the Haar Cascade Classifier.
- Within each detected face, it further detects smiles and eyes.
- Draws rectangles around detected features:
- Green rectangles for faces.
- Red rectangles for smiles.
- Blue rectangles for eyes.
- Displays the annotated video feed in a window.
- Closes the window and releases the webcam when 'q' is pressed.








