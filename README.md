# face-detect

Python face recognition program

Given a datset of images, encode_faces runs each image through a neural network to generate a 128-d vector, which is used to distinguish certain faces.
The images are then compared to the example images provided, outputting any faces detected along with names provided.

Packages used:
- imutils
- face_recognition
- argparse
- pickle
- opencv/cv2
- os
- cmake
- requests
