# LiveFilter

An implementation of OpenCV and Digital Image Processing.

This is a mini-project made using libraries like stow, mediapipe, tqdm, cv2, numpy, and typing to simulate the filters provided by different platforms like snapchat, etc.

It contains 4 files:

1. engine.py:- This file is responsible of image input and processing using webcam. It uses the cv2, stow, typing, numpy, tdqm libraries. It also depends on the selfiesegmentation for object detection.
2. selfieSegmentation.py:- It segments the object from the background. It uses the cv2, stow, typing, numpy, and mediapipe libraries.
3. pencilSketch.py:- It applies the pencil sketch filter over the frames. It uses the cv2, numpy, and typing libraries. This takes the frame after it is processed by engine.py and selfieSegmentation.py and implements the filter.
4. main.py:- This file combines all the 3 other files to produce output.

For any other custom filter, add the filter file and run it instead of pencilSketch.py.
