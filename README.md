# Face-Recognition
Face Recognition Using Opencv
Dependency :
pip install dlib
pip install face_recognition
pip install imutils
using dataset
python face-encoding.py --dataset dataset --encodings encodings.pickle --detection-method hog
run program
python face-recognition-video.py --cascade haarcascade_frontalface_default.xml --encodings encodings.pickle
