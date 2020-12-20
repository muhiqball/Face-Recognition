# Face-Recognition
Face Recognition Using Opencv
Dependency :
sudo apt install cmake build-essential pkg-config git
sudo apt install libjpeg-dev libtiff-dev libjasper-dev libpng-dev libwebp-dev libopenexr-dev
sudo apt install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev libxvidcore-dev libx264-dev libdc1394-22-dev libgstreamer-plugins-base1.0-dev libgstreamer1.0-dev
sudo apt install libgtk-3-dev libqtgui4 libqtwebkit4 libqt4-test python3-pyqt5
sudo apt install libatlas-base-dev liblapacke-dev gfortran
sudo apt install libhdf5-dev libhdf5-103
sudo apt install python3-dev python3-pip python3-numpy
pip install dlib
pip install face_recognition
pip install imutils
using dataset
python face-encoding.py --dataset dataset --encodings encodings.pickle --detection-method hog
run program
python face-recognition-video.py --cascade haarcascade_frontalface_default.xml --encodings encodings.pickle
